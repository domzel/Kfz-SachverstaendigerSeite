<template>
  <div class="min-h-screen flex flex-col">
    <header class="flex-none">
      <Navbar />
    </header>
    <main class="flex-grow">
      <slot />
    </main>
    <footer class="mt-24 flex-none">
      <div class="footer p-10 text-black">
        <nav>
          <header class="footer-title">© Damian Zelder - Kfz-Sachverständiger</header>
        </nav>
        <nav>
          <NuxtLink to="/kontakt" class="link link-hover">Kontakt</NuxtLink>
        </nav>
        <nav>
          <NuxtLink to="/impressum" class="link link-hover">Impressum</NuxtLink>
        </nav>
        <nav>
          <NuxtLink to="/datenschutz" class="link link-hover">Datenschutz</NuxtLink>
        </nav>
      </div>
    </footer>
  </div>
</template>

<script setup lang="ts">
import Navbar from "~/components/Navbar.vue";
useHead({
  title: "Kfz-Sachverständiger Damian Zelder"
})
</script>