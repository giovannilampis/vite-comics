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

  <div class="container">

    <AppHeader/>

    <AppMain/>

    <AppFooter/>

  </div>
 
</template>

<style lang="scss">

</style>
