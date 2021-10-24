<template>
  <div style="background-color:black;display:flex;justify-content:center;align-items:center;">   
      
      <div>
      <p class="bannerTitle">Potencialize suas vendas<br /> On-line.</p>
      <p class="bannerSubtitle">A Astrapack tem a solução completa de <b>madtech</b> para sua empresa</p>
      </div>
      <video style="max-width:900px;" controls autoplay loop src="../assets/bannermovie.mp4"></video>

  </div>
</template>

<script>
 

  export default {
    name: 'Banner',

    components: {
      //
    },
  }
</script>


<style lang="scss">
@import './src/sass/variables.scss';

.bannerTitle {
    font-size: 40px;
    font-family: $body-font-family;
}
.bannerSubtitle {
    font-family: $subtitle-font-family;
    font-size: 16px;
    font-weight: 100;
}

</style>