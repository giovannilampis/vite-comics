<script>
import AppHeader from './components/AppHeader.vue';
import AppFooter from './components/AppFooter.vue';
import AppMain from './components/AppMain.vue';

export default {
  data() {
    return {
      count: 0
    }
  },components:{AppHeader, AppFooter, AppMain}
}
</script>

<template>

  
  <AppHeader/>



  <AppMain/>



  <AppFooter/>
 
</template>

<style lang="scss">

  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

</style>
