<!-- filepath: /C:/Users/jelli/Website/landing-page/src/views/LandingPage.vue -->
<template>
  <div class="flex flex-col items-center justify-center min-h-screen">
    <h2 class="text-4xl mb-8">Elliot Stocker</h2>
    <p class="gray-100 text-1xl mb-8">Music site coming soon</p>
    <div class="space-x-4">
      <button @click="goToSubdomain1" class="bg-blue-500 text-white px-4 py-2 rounded hover:bg-blue-600">Music</button>
      <button @click="goToSubdomain2" class="bg-blue-500 text-white px-4 py-2 rounded hover:bg-blue-600">Portfolio</button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'LandingPage',
  methods: {
    goToSubdomain1() {
      window.location.href = '';
    },
    goToSubdomain2() {
      window.location.href = 'https://portfolio.elliotstocker.net';
    }
  }
}
</script>

<style scoped>
@keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}

div {
  animation: fadeIn 1s;
}

button {
  animation: fadeIn 1s;
  width: 100px;
}
</style>