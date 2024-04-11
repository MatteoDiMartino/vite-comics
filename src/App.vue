<script>
import boxheader from './components/boxheader.vue';
import boxmain from './components/boxmain.vue';


export default {
  components: {
    boxheader,
    boxmain
  }
}

</script>

<template>

<boxheader></boxheader>
<boxmain></boxmain>

</template>

<style lang="scss">
  @use './style/generic.scss'
</style>
