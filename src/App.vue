<script setup>
import HelloWorld from './components/HelloWorld.vue'
import Navmenu from './components/Navmenu.vue';
import Herosection from './components/Herosection.vue';
import Features from './components/Features.vue';
import Pricing from './components/Pricing.vue';
import Contact from './components/Contact.vue';
import Footer from './components/Footer.vue';




</script>

<template>
  <!-- <div>
    <a href="https://vitejs.dev" target="_blank">
      <img src="/vite.svg" class="logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a>
  </div>
  <HelloWorld msg="Vite + Vue" /> -->
  <Navmenu/>
  <Herosection/>
  <Features/>
  <Pricing/>
  <Contact/>
  <Footer/>

</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
