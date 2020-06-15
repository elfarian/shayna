<template>
  <div class="home">
    <HeaderShayna/>
    <HerroShayna/>
    <WomanShayna/>
    <InstaShayna/>
    <PartnerShayna/>
    <FooterShayna/>
  </div>
</template>

<script>
// @ is an alias to /src
//import HelloWorld from '@/components/HelloWorld.vue'
import HeaderShayna from '@/components/HeaderShayna.vue'
import HerroShayna from '@/components/HerroShayna.vue'
import WomanShayna from '@/components/WomanShayna.vue'
import InstaShayna from '@/components/InstaShayna.vue'
import PartnerShayna from '@/components/PartnerShayna.vue'
import FooterShayna from '@/components/FooterShayna.vue'


export default {
  name: 'Home',
  components: {
    HeaderShayna,
    HerroShayna,
    WomanShayna,
    InstaShayna,
    PartnerShayna,
    FooterShayna,
  }
};
</script>
