<template>
  <div style="display:flex;flex-direction:column;justify-content:center;">
    <Banner />
    <Road />
    <Who />
  </div>
</template>

<script>
 import Banner from '../components/Banner.vue'
 import Road from '../components/Road.vue'
 import Who from '../components/Who.vue'

  export default {
    name: 'Home',

    components: {
      Banner,
      Road,
      Who
    },
  }
</script>
