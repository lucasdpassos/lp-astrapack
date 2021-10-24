<template>
  <div style="background-color:black;display:flex;flex-direction:column;justify-content:center;align-items:center;height:700px;">   

      <p class="roadTitle">Como funciona o Pack?</p>

        <div style="display:flex;flex-direction:row">
       <v-img style="max-width:100px;" src="../assets/bar.png" />
       <video style="max-width:1100px;" controls autoplay loop src="../assets/road.mp4"></video>
       </div>

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

.roadTitle {
    font-size: 40px;
    font-family: $subtitle-font-family;
}


</style>