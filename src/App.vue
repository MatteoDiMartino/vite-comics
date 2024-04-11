<script>
import boxheader from './components/boxheader.vue';
import boxmain from './components/boxmain.vue';
import boxfooter from './components/boxfooter.vue';



export default {
  components: {
    boxheader,
    boxmain,
    boxfooter
  }
}

</script>

<template>

  <boxheader></boxheader>
  <boxmain></boxmain>
  <boxfooter></boxfooter>

</template>

<style lang="scss">
  @use './style/generic.scss'
</style>
