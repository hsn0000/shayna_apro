<template>
  <div class="home">
    <HeaderShayna />
    <HeroShayna />
    <WomanShayna />
    <InstaShayana />
    <PartnerShaya />
    <FooterShayna />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderShayna from "@/components/HeaderShayna.vue";
import HeroShayna from "@/components/HeroShayna.vue";
import WomanShayna from "@/components/WomanShayna.vue";
import InstaShayana from "@/components/InstaShayana.vue";
import PartnerShaya from "@/components/PartnerShaya";
import FooterShayna from "@/components/FooterShayna";

export default {
  name: "Home",
  components: {
    HeaderShayna,
    HeroShayna,
    WomanShayna,
    InstaShayana,
    PartnerShaya,
    FooterShayna,
  },
};
</script>
