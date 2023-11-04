<template>
  <header>
    <div class="navbar bg-white">
      <div class="navbar-start">
        <div class="dropdown">
          <label tabindex="0" class="btn btn-ghost lg:hidden">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h8m-8 6h16" /></svg>
          </label>
          <ul tabindex="0" class="menu menu-sm dropdown-content mt-3 z-[1] p-2 shadow bg-base-100 rounded-box w-52"> <!-- Sidebar -->
            <li><NuxtLink to="/">Home</NuxtLink></li>
            <li>
              <a>Unfall</a>
              <ul class="p-2">
                <li><NuxtLink to="/unfall/begriffsinfo">Begriffsinfo</NuxtLink></li>
                <li><NuxtLink to="/unfall/wastuen">Unfall was tuen?</NuxtLink></li>
                <li><NuxtLink to="/unfall/totalschaden">Totalschaden was tuen?</NuxtLink></li>
                <li><NuxtLink to="/unfall/lackierfehler">Lackierfehler</NuxtLink></li>
              </ul>
            </li>
            <li><NuxtLink to="/leistungen">Leistungen</NuxtLink></li>
            <li><NuxtLink to="/rechte">Ihr Recht</NuxtLink></li>
          </ul>
        </div> <!-- Sidebar ende -->
        <NuxtLink to="/" class="btn btn-ghost big-case text-xl h-1/2 m-3 text-black">Kfz-Sachverständiger <br>Damian Zelder</NuxtLink>
      </div>
      <div class="navbar-center hidden lg:flex">
        <ul class="menu menu-horizontal px-1">
          <li><NuxtLink to="/">Home</NuxtLink></li>
          <li tabindex="0">
            <details>
              <summary>Unfall</summary>
              <ul class="p-2">
                <li><NuxtLink to="/unfall/begriffsinfo">Begriffsinfo</NuxtLink></li>
                <li><NuxtLink to="/unfall/wastuen">Unfall was tuen?</NuxtLink></li>
                <li><NuxtLink to="/unfall/totalschaden">Totalschaden was tuen?</NuxtLink></li>
                <li><NuxtLink to="/unfall/lackierfehler">Lackierfehler</NuxtLink></li>
              </ul>
            </details>
          </li>
          <li><NuxtLink to="/leistungen">Leistungen</NuxtLink></li>
          <li><NuxtLink to="/rechte">Ihr Recht</NuxtLink></li>
        </ul>
      </div>
      <div class="navbar-end">
        <p class="btn btn-ghost text-xl m-3 text-black">LOGO</p>
      </div>
    </div>
  </header>
  <div class="container">
    <slot></slot>
  </div>

  <footer>
    <nav>
      <NuxtLink to="/">Test</NuxtLink>
    </nav>
  </footer>
</template>

<style scoped>
.router-link-exact-active {
  color: #12b488;
}
</style>
<script setup lang="ts">

</script>