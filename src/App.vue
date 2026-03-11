<template>
  <Navbar />
  <router-view/>
  <Footer />
</template>


<script setup>
  import Navbar from './components/Navbar.vue';
  import Footer from './components/Footer.vue';


    components: {
      Navbar,
      Footer
    }

</script>



<style>

</style>
