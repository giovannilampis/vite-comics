<script>
import AppHeader from './components/AppHeader.vue';
export default {
  data() {
    return {
      count: 0
    }
  },components:{AppHeader}
}
</script>

<template>

  <div class="container">

    <AppHeader/>

    <main>

      <div class="provisional-content">
        Content goes here
      </div>

    </main>


    <footer>

      <a href="#" class="text-uppercase">sign-up now</a>
    </footer>

  </div>
 
</template>

<style lang="scss">


  main {
    background-color: rgba(28, 28, 28, 1);
    color: rgba(255, 255, 255, 1);
  }

  .provisional-content {
    height: 6rem;
  }

  footer {
    height: 6rem;
    background-color: rgba(48, 48, 48, 1);
    color: rgba(255, 255, 255, 1);
  }

  footer a {
    color: rgba(255, 255, 255, 1);
    text-decoration: none;
  }

  .icon-bg {
    color: rgba(121, 121, 121, 1);
  }

</style>
