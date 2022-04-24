<template>
<div id="app">
  <!-- <IntroNfft /> -->
  <HeaderNav />
  <ContentMain />
  <ContentNft />
  <FooterNav />
  <ContentYoutube />
</div>
</template>

<script>
  import HeaderNav from './components/HeaderNav.vue'
  // import FooterNav from './components/FooterNav.vue'
  import ContentMain from './components/ContentMain.vue'
  import ContentNft from './components/ContentNft.vue'
  import ContentYoutube from './components/ContentYoutube.vue'

  export default {
  name: 'App',
  components: {
      HeaderNav,
      ContentMain,
      ContentNft,
      ContentYoutube,
      // FooterNav,
      // IntroNfft,
    }
  }
</script>

<style>
#app {
  font-family: 'Poppins';
}
</style>
