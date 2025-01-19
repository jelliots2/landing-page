<template>
  <MainLayout>
    <NavBar />
    <router-view />
    <FooterBar />
  </MainLayout>
</template>

<script>
import MainLayout from './components/Layout.vue';
import NavBar from './components/NavBar.vue';
import FooterBar from './components/Footer.vue';

export default {
  name: 'App',
  components: {
    MainLayout,
    NavBar,
    FooterBar
  }
};
</script>