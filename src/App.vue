<template>
  <div id="app">
    <headerNav />
    <!-- <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <router-view/> -->
  </div>
</template>

<script>
// @ is an alias to /src

import headerNav from "@/components/headerNav.vue";

export default {
  name: "home",
  components: {
    headerNav
  }
};
</script>

<style>
</style>
