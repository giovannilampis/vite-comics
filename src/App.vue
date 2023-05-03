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

.container AppHeader {
  background-color: rgba(255, 255, 255, 1);
}

.container AppMain {
  background-color: rgba(28, 28, 28, 1);
}

.container AppFooter {
  background-color: rgba(48, 48, 48, 1);
}

</style>
