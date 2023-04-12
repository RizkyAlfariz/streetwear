<template>
  <div class="home">
    <HeaderStreetwear />
    <HeroStreetwear />
    <BannerStreetwear />
    <InstaStreetwear />
    <PartnerStreetwear />
    <FooterStreetwear />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";
import HeaderStreetwear from "@/components/HeaderStreetwear.vue";
import HeroStreetwear from "@/components/HeroStreetwear.vue";
import BannerStreetwear from "@/components/BannerStreetwear.vue";
import InstaStreetwear from "@/components/InstaStreetwear.vue";
import PartnerStreetwear from "@/components/PartnerStreetwear.vue";
import FooterStreetwear from '@/components/FooterStreetwear.vue';



export default {
  name: "HomeView",
  components: {
    HeaderStreetwear,
    HeroStreetwear,
    BannerStreetwear,
    InstaStreetwear,
    PartnerStreetwear,
    FooterStreetwear,
  },
};
</script>
