<!-- filepath: /C:/Users/jelli/Website/landing-page/src/views/AboutPage.vue -->
<template>
    <div class="flex flex-col items-center justify-center min-h-screen">
      <h1 class="text-4xl mb-4">About Me</h1>
      <p class="text-lg text-center max-w-prose">I am a Full-Stack Web Developer and hobbyist music producer.</p>
    </div>
</template>

<script>
export default {
  name: 'AboutPage'
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
  color: white;
  animation: fadeIn 1s;
}
</style>