<script>
import boxheader from './components/boxheader.vue';
import boxmain from './components/boxmain.vue';
import boxfooter from './components/boxfooter.vue';
import boxcard from './components/boxcard.vue';


export default {
  components: {
    boxheader,
    boxmain,
    boxfooter,
    boxcard
  },
  data() {
    return {
      
    }
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
