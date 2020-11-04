<template>
  <div class="home">
    <HeaderMocha />
    <HeroMocha />
    <ItemSMocha />
    <InstaMocha />
    <PartnerLogoMocha />
    <FooterMocha />
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderMocha from '@/components/HeaderMocha.vue'
import HeroMocha from '@/components/HeroMocha.vue'
import ItemSMocha from '@/components/ItemSMocha.vue'
import InstaMocha from '@/components/InstaMocha.vue'
import PartnerLogoMocha from '@/components/PartnerLogoMocha.vue'
import FooterMocha from '@/components/FooterMocha.vue'


export default {
  name: 'Home',
  components: {
    HeaderMocha,
    HeroMocha,
    ItemSMocha,
    InstaMocha,
    PartnerLogoMocha,
    FooterMocha
  }
}
</script>
