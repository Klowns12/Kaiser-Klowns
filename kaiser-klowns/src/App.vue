<template>
  <nav class="flex justify-between items-center p-3 bg-white">
    <div class="logo">
      <img src=".\assets\image\RedGiant.png" alt="Kaiser Klowns Logo" class="h-12" />
    </div>
    <div class="brand-name">
      <h1 class="text-red-700 text-3xl text-center font-engravers">Kaiser Klowns</h1>
    </div>
    <div class="icons flex">
      <router-link to="/" class="text-white hover:text-yellow-400 mx-2">
        <i class="fas fa-home"></i>
      </router-link>
      <router-link to="/cart" class="text-white hover:text-yellow-400 mx-2">
        <i class="fas fa-shopping-cart"></i>
      </router-link>
      <router-link to="/profile" class="text-white hover:text-yellow-400 mx-2">
        <i class="fas fa-user"></i>
      </router-link>
    </div>
  </nav>


  <HomePage msg="Welcome to Your Vue.js App"/>
</template>

<script>
import HomePage from './components/HomePage.vue';
export default {
  name: 'App',
  components: {
    HomePage
  }
}
</script>

<style>

</style>
