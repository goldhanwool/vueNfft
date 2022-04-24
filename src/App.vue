<template>
<div id="app">
  <!-- <IntroNfft /> -->
  <HeaderNav />
  <ContentMain />
  <ContentNft />
  <IntroNft />
  <ContentYoutube />
  <ContentValue />
  <ContentFAQ />
  <ContentTeam/>
  <FooterNav />
</div>
</template>

<script>
  import HeaderNav from './components/HeaderNav.vue'
  // import FooterNav from './components/FooterNav.vue'
  import ContentMain from './components/ContentMain.vue'
  import ContentNft from './components/ContentNft.vue'
  import IntroNft from './components/IntroNft.vue'
  import ContentYoutube from './components/ContentYoutube.vue'
  import ContentValue from './components/ContentValue.vue'
  import ContentFAQ from './components/ContentFAQ.vue'
  import ContentTeam from './components/ContentTeam.vue'


  export default {
  name: 'App',
  components: {
      HeaderNav,
      ContentMain,
      ContentNft,
      IntroNft,
      ContentYoutube,
      ContentValue,
      ContentFAQ,
      ContentTeam,
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
