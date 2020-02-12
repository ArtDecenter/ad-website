<template>
  <div>
    <div class="w-full flex">
      <div class="w-1/4 mx-auto" v-for="overview in overviewBoxes" v-bind:key="overview">
        <h1 class="fontMono text-xl pb-4 italic">{{ overview.headline }}</h1>
        <p class="fontInter font-base">{{ overview.text }}</p>
      </div>
    </div>
    <div
      class="fontMono italic w-4/5 text-center mx-auto py-24 leading-snug text-5xl"
    >ArtDecenter connects participants of the art market peer-to-peer, by providing a decentralized platform accessible through an easy-to-use application.</div>
  </div>
</template>

<script>
export default {
  name: "Overview",
  data() {
    return {
      overviewBoxes: [
        {
          headline: "peer-to-peer",
          text:
            "Lorem ipsum dolor sit amet consectetur adipisicing elit. Nulla numquam ratione quo porro aliquam corrupti quisquam dolorum, quasi nobis nam!"
        },
        {
          headline: "modular",
          text:
            "Lorem ipsum dolor sit amet consectetur adipisicing elit. Nulla numquam ratione quo porro aliquam corrupti quisquam dolorum, quasi nobis nam!"
        },
        {
          headline: "accessible",
          text:
            "Lorem ipsum dolor sit amet consectetur adipisicing elit. Nulla numquam ratione quo porro aliquam corrupti quisquam dolorum, quasi nobis nam!"
        }
      ]
    };
  }
};
</script>

<style>
</style>