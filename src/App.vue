<template>
  <div id="app">
    <headerNav />
    <!-- <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <router-view/> -->
    <hero />
    <!-- <Footer /> -->
  </div>
  
</template>

<script>
// @ is an alias to /src

import headerNav from "@/components/headerNav.vue";
import hero from "@/components/hero.vue";
// import Footer from "@/components/footer.vue";

export default {
  name: "home",
  components: {
    headerNav,
    hero,
    
  }
};
</script>

<style>
#app {
  font-family: "IBM Plex Mono", "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

</style>
