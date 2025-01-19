<!-- filepath: /C:/Users/jelli/portfolio/vue-portfolio/src/components/NavBar.vue -->
<template>
  <nav class="fixed top-0 left-0 w-full p-4 bg-transparent z-10">
    <ul class="flex space-x-4 justify-center">
      <li><router-link to="/" class="text-white hover:text-gray-300">Home</router-link></li>
      <li><router-link to="/about" class="text-white hover:text-gray-300">About</router-link></li>
    </ul>
  </nav>
</template>

<script>
export default {
  name: 'NavBar'
};
</script>

<style scoped>
nav {
  background-color: transparent !important;
}

</style>