<template>
  <div id="app">
    <HeaderComp/>
    <JumbotronComp/>
    <MainComp/>
    <SectionShopComp/>
    <FooterComp/>

  </div>
</template>

<script>
import HeaderComp from './components/HeaderComp.vue'
import MainComp from './components/MainComp.vue'
import SectionShopComp from './components/SectionShopComp.vue'
import FooterComp from './components/FooterComp.vue'
import JumbotronComp from './components/JumbotronComp.vue'

export default {
  name: 'App',
  components: {
    HeaderComp,
    MainComp,
    SectionShopComp,
    FooterComp,
    JumbotronComp,
  }
}
</script>

<style lang="scss">
//general
@import './assets/style/general.scss';
</style>
