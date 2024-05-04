<template>
  <section
    class="p-1  h-screen"
  >
    <div
      class="mt-52 mx-auto max-w-screen-xl text-center lg:py-16 z-10 relative"
    >
      <h1
        class="mb-4 text-4xl font-extrabold tracking-tight leading-none text-gray-900 md:text-5xl lg:text-6xl dark:text-white"
      >
        Daniel Iván López García
      </h1>
      <p
        class="mb-8 text-lg font-normal text-gray-500 lg:text-xl sm:px-16 lg:px-48 dark:text-gray-200"
      >
        Estudiante, Analista y Desarrollador FullStack.
      </p>
      <form class="w-full max-w-md mx-auto">
        <div class="relative">
          <a href="https://www.github.com/divan1319" target="blank">
            <Chip label="GitHub" icon="pi pi-github" />
          </a>
          <a href="https://api.whatsapp.com/send?phone=50371732401">
            <Chip label="WhatsApp" icon="pi pi-whatsapp"  />
          </a>
        </div>
      </form>
    </div>
    <div
      class="bg-gradient-to-b from-blue-50 to-transparent dark:from-blue-900 w-full h-full absolute top-0 left-0 z-0"
    ></div>
  </section>
</template>

<script setup>
import Chip from "primevue/chip";
</script>
