<template>
  <div class="p-6 md:p-12 mx-auto">
    <p
          class="md:w-3/4 w-full text-center mx-auto text-gray-800 py-2 text-2xl md:text-4xl leading-tight font-bold"
        >
          A market as open as art itself
        </p>

        <p class="w-full md:w-1/2 mx-auto pt-8 text-gray-800 text-center md:text-left">
          We are building a
          <span class="highlight-text">decentralized application</span>
          focusing on trustless interaction between artists, art enthusiasts,
          museums & collectors.
        </p>
        <p class="w-full md:w-1/2 mx-auto text-gray-800 text-center md:text-left pt-4">By rethinking the structure of ownership and
          value distribution, we adopt web3 standards to the art market.</p>

          <div class="w-full md:w-1/2 pt-8 mx-auto text-gray-800 text-center md:text-left sm:inline md:hidden">coming soon</div>
   
    
  </div>
</template>

<script>
export default {
  name: 'hero',
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.highlight-text{
  @apply bg-gray-200 p-1 font-bold rounded-lg
}
</style>
