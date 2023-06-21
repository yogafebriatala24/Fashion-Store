<template>
  <div class="home">
    <HeaderFashion />
    <HeroFashion />
    <WomenFashion />
    <InstaFashion />
    <PartnerFashion />
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

import HeaderFashion from "@/components/HeaderFashion.vue";
import HeroFashion from "@/components/HeroFashion.vue";
import WomenFashion from "@/components/WomenFashion.vue";
import InstaFashion from "@/components/InstaFashion.vue";
import PartnerFashion from "@/components/PartnerFashion.vue";
import Footer from "@/components/Footer.vue";

export default {
  name: "home",
  components: {
    HeaderFashion,
    HeroFashion,
    WomenFashion,
    InstaFashion,
    PartnerFashion,
    Footer,
  },
};
</script>
