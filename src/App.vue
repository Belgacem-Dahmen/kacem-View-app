<script setup>
import {  RouterView } from 'vue-router'
import Navbar from './components/Navbar.vue';
import AsideBar from './components/AsideBar.vue';
</script>

<template>
  <header>
    <Navbar />
    
  </header>
  <section class=" flex p-0 h-screen">
    <AsideBar />
    <main class="m-4 w-full">
      <RouterView />
    </main>
    



  </section>
  
</template>

<style scoped>

</style>
