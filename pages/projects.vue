<template>
  <main class="min-h-screen">
    <AppHeader class="mb-12" title="Proyectos" :description="description" />
    <div class="space-y-4">
      <AppProjectCard v-for="(project, id) in projects" :key="id" :project="project" />
    </div>
  </main>
</template>

<script setup>
const description =
  "Proyectos seleccionados en los que he trabajado ultimamente.";
useSeoMeta({
  title: "Proyectos | Luis Arteaga",
  description,
});

const { data: projects } = await useAsyncData("projects-all", () =>
  queryContent("/projects").find()
);
</script>
