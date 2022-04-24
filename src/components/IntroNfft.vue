<template>
  <div class="intro">
    <p class='text_style_normal position'>Soon <span class='text_style_huge'>NFFT</span> will be connected to the <span class='text_style_bold'>world</span></p>
    <div class="img">  
      <img src = "@/assets/facebook.png" />
      <img src = "@/assets/youtube.png" />
    </div>
  </div>
</template>

<script> 
  export default {
    name: 'IntroNfft',
  }
</script>

<style>
.intro {
  width: 100vw;
  height: 100vh;
  background: linear-gradient(0deg, rgba(236, 233, 255, 1), rgba(252, 252, 255, 1));
}

.text_style_normal {
  font-family: 'Poppins';
  font-size: 60px;
  font-weight: 600;
}

.position {
  margin-left : 100px;
  margin-top: 200px;
}

.text_style_huge {
  font-family: 'Poppins';
  font-size: 120px;
  font-weight: 700;
}

.text_style_bold {
  font-family: 'Poppins';
  font-size: 60px;
  font-weight: 2400;
}

img {
  margin-left: 100px;

}

</style>
