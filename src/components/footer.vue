<template lang="html">
  <!-- footer total -->

  <div id="FooterTotal " class="border-t border-gray-400 w-11/12 mx-auto py-12">
    <!-- social links -->

    <div id="FooterWrapper" class="">
      

      <!-- logo & contact -->

      <div class="">
        <img src="@/assets/artdecenter-logo.svg" alt="" class="mx-auto">
      </div>

      <div class="pt-8 text-base tracking-wide leading-tight">
        <div class="text-center ">
          <!-- <a class="hover:text-white" href="mailto:info@artdecenter.com"
            >Contact us</a
          > -->
           &copy; Berlin, 2020
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Footer",
  components: {},

  data() {
    return {
      window: window,
      socialLinks: [
        {
          name: "Github",
          message:
            "Contribute to our open source project by visiting our repositories.",
          src: require("@/assets/social/github.svg"),
          href: "https://github.com/artdecenter"
        },
        // {
        //   name: "Discord",
        //   message: "Join the community and participate in ongoing discussions.",
        //   src: require("@/assets/social/discord.svg"),
        //   href: "https://discord.gg/QqM9pMz"
        // },
        {
          name: "Twitter",
          message: "Follow @artdecenter to be notified of future updates.",
          src: require("@/assets/social/twitter.svg"),
          href: "https://twitter.com/artdecenter"
        }
      ]
    };
  },

  computed: {}
};
</script>

<style lang="postcss" scoped>
#FooterTotal {
  @apply;
}
#FooterWrapper {
  @apply .mx-auto;
}
#SocialLinksDiv {
  @apply .mx-auto .flex .flex-wrap .justify-around .text-center;
}
.SocialLinkContainer {
  @apply .py-4 .py-12;
}
.SocialLinkIcon {
  @apply .w-12 .h-12 .px-1 .text-center .mx-auto .cursor-pointer;
}
.SocialLinkName {
  @apply .tracking-wide .pt-6 .p-1 .text-white .cursor-pointer;
}
.SocialLinkMessage {
  @apply .p-2 .text-base .tracking-wide .leading-tight .inline-block;
}

@media screen and (max-width: 640px) {
  .SocialLinkName {
    @apply .hidden;
  }
  .SocialLinkMessage {
    @apply .hidden;
  }
}
@media screen and (min-width: 768px) {
}
@media screen and (min-width: 1024px) {
}
@media screen and (min-width: 1280px) {
}
</style>
