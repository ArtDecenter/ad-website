<template>
  <div>
    <div class="w-full mx-auto flex justify-around">
      <div class="w-1/4" v-for="overview in overviewBoxes" v-bind:key="overview">
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
            "A truly open market needs to connect its participants permissionless and without middlesman. That's why our platform is based on web3 standards powered by the Ethereum blockchain."
        },
        {
          headline: "customizable",
          text:
            "We are bridging the gap between the art market and digital innovation. By offering a modular plugin approach for our ÐApp, you can choose what features you want to make us of to get started."
        },
        {
          headline: "accessible",
          text:
            "Our goal is it to simplify the process of interacting with the blockchain, by offering a simple and straightforward interface. Get the best of blockchain without the need to code a single line. "
        }
      ]
    };
  }
};
</script>

<style>
</style>