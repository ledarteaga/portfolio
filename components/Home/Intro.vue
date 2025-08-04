<template>
  <div class="space-y-6">
    <NuxtImg src="/avatar.jpeg" alt="Fayaz Ahmed"
      class="ring-2 border ring-gray-200 border-gray-300 dark:ring-white/10 dark:border-gray-800 hover:ring-4 transition-all duration-300 bg-gray-200 dark:bg-gray-900 rounded-full h-12 w-12 sm:h-16 sm:w-16"
      sizes="48px sm:64px" placeholder format="webp" />
    <h1 class="text-xl  tracking-tight text-gray-800 dark:text-gray-100">
      <span class=" font-bold bg-gradient-to-r from-pink-500 to-violet-500 bg-clip-text text-transparent">¡Hola!</span>
      Soy Luis
      Arteaga
    </h1>
    <p class="text-gray-900 dark:text-gray-400">

      Desarrollador web con experiencia en Vue, Typescript y Flutter. Enfocado en crear webs y aplicaciones que
      generan resultados.
      <br>
      <br>
      He desarrollado webs para aumentar las ventas, aplicaciones para mejorar la experiencia del cliente y soluciones
      digitales que optimizan la gestión de negocios.
      <br>
      <br>
      ¿Quieres saber cómo puedo ayudarte? Contactame y juntos construiremos la solución perfecta para tu negocio.
    </p>
    <p class="text-gray-900 dark:text-gray-400">
      Actualmente un desarrollador frontend en
      <a href="https://www.balidea.com" target="_blank" class="underline">Balidea Consulting</a>.
    </p>
  </div>
</template>

<script setup>
useSeoMeta({
  title: "Luis Arteaga | Frontend Developer",
  description:
    "Soy un desarrollador frontend con experiencia en Vue, Typescript y Flutter que te ayuda a crear webs y aplicaciones que generan resultados.",
});
</script>
