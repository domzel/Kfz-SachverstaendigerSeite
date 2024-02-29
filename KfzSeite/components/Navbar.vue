<template>
  <div class="navbar bg-white text-black md:mb-10 items-center">
    <div class="flex flex-grow md:hidden mx-5">
      <button @click="toggleMenu" class="text-black focus:outline-none">
        <svg class="h-6 w-6" fill="none" viewBox="0 0 24 24" :stroke="strokeColor">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path>
        </svg>
      </button>
    </div>

    <div class="hidden md:flex flex-row flex-grow">
      <NuxtLink to="/" class="btn btn-ghost text-xl">Startseite</NuxtLink>
      <NuxtLink to="/leistungen" class="btn btn-ghost text-xl">Leistungen</NuxtLink>
      <div class="dropdown dropdown-end">
        <label tabindex="0" class="btn btn-ghost text-xl">
          Unfall
        </label>
        <ul tabindex="0" class="mt-2 z-[1] p-2 shadow menu menu-sm dropdown-content bg-white rounded-box w-auto">
          <li>
            <NuxtLink to="/unfall/begriffsinfo">Begriffsinfo</NuxtLink>
          </li>
          <li>
            <NuxtLink to="/unfall/wastuen">Unfall was tun?</NuxtLink>
          </li>
          <li>
            <NuxtLink to="/unfall/totalschaden">Totalschaden was tun?</NuxtLink>
          </li>
          <li>
            <NuxtLink to="/unfall/lackierfehler">Lackierfehler</NuxtLink>
          </li>
        </ul>
      </div>
      <NuxtLink to="/rechte" class="btn btn-ghost text-xl">Ihr Recht</NuxtLink>
      <NuxtLink to="/fotogalerie" class="btn btn-ghost text-xl">Fotogalerie</NuxtLink>
    </div>
    </div>


  <!-- Mobile Menu (hidden by default) -->
  <div v-if="isMenuOpen" class="md:hidden bg-white text-black flex flex-grow
     justify-start p-5 flex-col mb-10">
    <NuxtLink to="/" class="btn btn-ghost text-xl">Startseite</NuxtLink>
    <br>
    <NuxtLink to="/leistungen" class="btn btn-ghost text-xl">Leistungen</NuxtLink>
    <br>
    <div class="dropdown dropdown-end items-center">
      <label tabindex="0" class="btn btn-ghost text-xl">
        Unfall
      </label>
      <ul tabindex="0" class="shadow menu menu-sm dropdown-content bg-white rounded-box w-auto">
        <li>
          <NuxtLink to="/unfall/begriffsinfo">Begriffsinfo</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/unfall/wastuen">Unfall was tun?</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/unfall/totalschaden">Totalschaden was tun?</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/unfall/lackierfehler">Lackierfehler</NuxtLink>
        </li>
      </ul>
    </div>
    <br>
    <NuxtLink to="/rechte" class="btn btn-ghost text-xl">Ihr Recht</NuxtLink>
    <NuxtLink to="/fotogalerie" class="btn btn-ghost text-xl">Fotogalerie</NuxtLink>
  </div>
  <!-- End Mobile Menu -->
</template>

<script setup lang="ts">
const strokeColor = ref<String>("")
// #a6adbb
onMounted(() => {
  strokeColor.value = "#000000"
})

let isMenuOpen = ref()
isMenuOpen.value = false;

const toggleMenu = () => {
  isMenuOpen.value = !isMenuOpen.value;
}
</script>