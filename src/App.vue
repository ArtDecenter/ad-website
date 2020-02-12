<template>
  <div id="app" class="adRed font-base mx-auto">
    <div id="nav">
      <!-- <router-link to="/">Home</router-link>|
      <router-link to="/about">About</router-link>-->
    </div>
    <router-view />

    <!-- <Footer /> -->
  </div>
</template>

<script>
// @ is an alias to /src

// import Footer from "@/components/footer.vue";

export default {
  name: "home",
  components: {}
};
</script>

<style>
#app {
  font-family: "Inter", "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  max-width: 1280px;
}

.fontManrope {
  font-family: "Manrope", sans-serif;
}

.fontMono {
  font-family: "IBM Plex Mono", monospace;
}

.adRed {
  color: #ff1f00;
}
</style>
