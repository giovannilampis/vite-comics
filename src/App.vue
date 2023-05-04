<script>
import AppHeader from './components/AppHeader.vue';
import AppFooter from './components/AppFooter.vue';
import AppMain from './components/AppMain.vue';
import BlueSection from './components/BlueSection.vue';
import JumbotronSection from './components/JumbotronSection.vue';



export default {
  data() {
    return {
      count: 0
    }
  },components:{AppHeader, JumbotronSection, AppFooter, AppMain, BlueSection}
}
</script>

<template>

  
  <AppHeader/>

  <JumbotronSection/>

  <AppMain/>

  <BlueSection/>

  <AppFooter/>
 
</template>

<style lang="scss">

  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

</style>
