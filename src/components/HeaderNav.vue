<template>

  <div class="innerHeader">
    <h1 class="logo"><a href="index.html"><img src="@/assets/nfft_logo.png"></a></h1>
    <nav class="mainMenu">  
      <span class="bar"></span>
        <ul class="nfftMenu m">
          <li><a href="#">WORLD</a></li>
          <li><a href="#">ROADMAP</a></li>
          <li><a href="#">FAQ</a></li>
          <li><a href="#">NFFT</a></li>
          <li><a href="#">TEAM</a></li>
          <li><a class="metaMaskMy" href="">MY</a></li>
        </ul>
      </nav>
  </div>

</template>

<script>
import '@/assets/js/main.js'
import $ from 'jquery';

// 카테고리를 선택할 경우 호버가 될 수 있도록 하는 J_Query
export default {
  mounted() { 
    $('.nfftMenu li a').on('mouseenter focus', function() {
        var menuBar = $(this).position().left;
        var widNum = $(this).width();
        $('span.bar').css({'left':menuBar + 'px', 'width': widNum + 'px', opacity:1});
    });
    $('.nfftMenu li a').on('mouseenter', function() {
        $('span.bar').css({'left':0, 'width':0, 'opacity':0});
    });
}}

// export default {
  //   // name: 'HeaderNav',
  //   // data(){
  //   //   return {
  //   //       navList: ['WORLD','ROADMAP','FAQ','NFFT', 'TEAM'],
  //   //     }
  //   //   }
  // }

</script>

<style>
@import '@/assets/css/header.css'
</style>
