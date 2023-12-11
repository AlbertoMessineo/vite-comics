<script>
 import Header from './components/Header.vue'; 
 import Main from './components/Main.vue';
 import Footer from './components/Footer.vue';
 import { createApp } from 'vue';
 export default{
  name: createApp,
  components: {
  Header,
  Main,
  Footer,
 },
};

</script>
<template>
  <Header />
  <Main />
  <Footer />
</template>
<style lang="scss">
@use 'styles/partials/variables' as *;
@use './styles/generals' as *;
</style>