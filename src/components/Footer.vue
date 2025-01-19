<!-- filepath: /C:/Users/jelli/portfolio/vue-portfolio/src/components/Footer.vue -->
<template>
  <footer class="bg-gray-800 text-white py-4">
    <div class="container mx-auto text-center">
      <p>&copy; 2025 Jacob Elliot Stocker</p>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'FooterBar'
};
</script>

<style scoped>
footer {
  background-color: transparent; 
  color: #ffffff; 
  padding: 1rem 0; 
  position: fixed; 
  bottom: 0; 
  left: 0;
  width: 100%; 
}

a {
  color: #63b3ed; /* Tailwind's blue-400 */
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}
</style>