<template>
  <div class>
    <HeaderNav />
    <Hero />
    <Overview />
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderNav from "@/components/HeaderNav.vue";
import Hero from "@/components/Hero.vue";
import Overview from "@/components/Overview.vue";
import Footer from "@/components/Footer.vue";

export default {
  name: "home",
  components: {
    HeaderNav,
    Hero,
    Overview,
    Footer
  }
};
</script>
