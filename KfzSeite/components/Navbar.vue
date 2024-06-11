<template>
  <div class="navbar bg-white text-black md:mb-10 shadow-md">
    <div class="flex justify-between items-center w-full">
        <a href="/" class="flex items-center">
          <img src="/images/Logo.jpg" alt="Logo" class="w-52 h-16 mx-5" />
        </a>
      <div class="hidden md:flex flex-grow justify-center">
        <NuxtLink to="/" class="btn btn-ghost text-xl mx-2">Startseite</NuxtLink>
        <NuxtLink to="/leistungen" class="btn btn-ghost text-xl mx-2">Leistungen</NuxtLink>
        <div class="dropdown dropdown-hover">
          <label tabindex="0" class="btn btn-ghost text-xl mx-2">Unfall</label>
          <ul tabindex="0" class="p-2 shadow menu menu-compact dropdown-content bg-white rounded-box w-52">
            <li><NuxtLink to="/unfall/begriffsinfo">Begriffsinfo</NuxtLink></li>
            <li><NuxtLink to="/unfall/wastuen">Unfall was tun?</NuxtLink></li>
            <li><NuxtLink to="/unfall/totalschaden">Totalschaden was tun?</NuxtLink></li>
            <li><NuxtLink to="/unfall/lackierfehler">Lackierfehler</NuxtLink></li>
          </ul>
        </div>
        <NuxtLink to="/rechte" class="btn btn-ghost text-xl mx-2">Ihr Recht</NuxtLink>
        <NuxtLink to="/fotogalerie" class="btn btn-ghost text-xl mx-2">Fotogalerie</NuxtLink>
      </div>
      <div class="flex flex-col text-right mx-5 hidden md:block">
        <p class="text-lg">Schadengutachten, Beweissicherung, kostenlose Beratung</p>
        <p class="text-lg font-bold">24h Rufbereitschaft 0172 9999 006</p>
      </div>
      <div class="md:hidden flex items-center">
        <button @click="toggleMenu" class="text-black focus:outline-none">
          <svg class="h-6 w-6" fill="none" viewBox="0 0 24 24" :stroke="strokeColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path>
          </svg>
        </button>
      </div>
    </div>

    <!-- Mobile Menu -->
    <div v-if="isMenuOpen" class="md:hidden bg-white text-black flex flex-col p-5">
      <NuxtLink to="/" class="btn btn-ghost text-xl mb-4">Startseite</NuxtLink>
      <NuxtLink to="/leistungen" class="btn btn-ghost text-xl mb-4">Leistungen</NuxtLink>
      <div class="dropdown dropdown-hover">
        <label tabindex="0" class="btn btn-ghost text-xl mb-4">Unfall</label>
        <ul tabindex="0" class="p-2 shadow menu menu-compact dropdown-content bg-white rounded-box w-52">
          <li><NuxtLink to="/unfall/begriffsinfo">Begriffsinfo</NuxtLink></li>
          <li><NuxtLink to="/unfall/wastuen">Unfall was tun?</NuxtLink></li>
          <li><NuxtLink to="/unfall/totalschaden">Totalschaden was tun?</NuxtLink></li>
          <li><NuxtLink to="/unfall/lackierfehler">Lackierfehler</NuxtLink></li>
        </ul>
      </div>
      <NuxtLink to="/rechte" class="btn btn-ghost text-xl mb-4">Ihr Recht</NuxtLink>
      <NuxtLink to="/fotogalerie" class="btn btn-ghost text-xl">Fotogalerie</NuxtLink>
    </div>
  </div>
</template>

<script setup lang="ts">
const strokeColor = ref<String>("#000000");
const isMenuOpen = ref(false);

const toggleMenu = () => {
  isMenuOpen.value = !isMenuOpen.value;
};
</script>
