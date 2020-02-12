<template lang="html">
  <div class="">
    <div class="flex mx-auto p-8 lg:p-12 justify-between ">
      <div class="mx-auto md:mx-0">
        <router-link to="/"
          ><img src="@/assets/artdecenter-logo.svg" alt="" class=" w-48 lg:w-56"></router-link>

      </div>

      <div class="md:inline-flex hidden">
        <div><a href="https://twitter.com/ArtDecenter" target=”_blank”><img src="@/assets/social/twitter.svg" alt="" class="w-8 mx-2 opacity-50 hover:opacity-100"></a></div>
        <div><a href="https://github.com/ArtDecenter" target=”_blank”><img src="@/assets/social/github.svg" alt="" class="w-8 mx-2 opacity-50 hover:opacity-100"></a></div>
      </div>
      
      <!-- <div class="w-32 flex justify-between">
        <div class="">
          <router-link to="/">Home</router-link>
        </div>

        <div class="">
          <router-link to="/about">About</router-link>
        </div>
      </div> -->
    </div>

    
  </div>
</template>



<script>
export default {
  name: "HeaderNav"
};
</script>



<style lang="css" scoped></style>
