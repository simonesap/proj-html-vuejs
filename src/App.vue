<template>

  <div>
    
    <HeaderComp/>

    <MainComp/>

    <FooterComp/>

  </div>

</template>

<script>
import HeaderComp from './components/HeaderComp.vue'
import MainComp from './components/MainComp.vue'
import FooterComp from './components/FooterComp.vue'

export default {
  name: 'App',
  components: {
    HeaderComp,
    MainComp,
    FooterComp,
  }
}
</script>

<style lang="scss">
@import './assets/style/general.scss';
@import url('https://fonts.googleapis.com/css2?family=Nunito&display=swap');

  body {
    font-family: 'Nunito', sans-serif;
  }

</style>
