<!-- filepath: /C:/Users/jelli/portfolio/vue-portfolio/src/components/Layout.vue -->
<template>
  <div class="layout-container min-h-screen">
    <slot></slot>
  </div>
</template>

<script>
export default {
  name: 'MainLayout'
};
</script>

<style scoped>
.layout-container {
  background-color: #797979;
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  min-height: 100vh;
}
</style>