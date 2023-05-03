<script setup>

</script>

<template>

  <div class="container">

    <header class="d-flex">

        <div>
            <img src="../public/img/dc-logo.png" alt="logo">
        </div>

        <ul class="text-uppercase d-flex">
          
          <a href=""><li>characters</li></a>
          
          <a href=""><li>comics</li></a>
          
          <a href=""><li>movies</li></a>
          
          <a href=""><li>tv</li></a>
          
          <a href=""><li>games</li></a>
          
          <a href=""><li>collectibles</li></a>
          
          <a href=""><li>videos</li></a>
          
          <a href=""><li>fans</li></a>
          
          <a href=""><li>news</li></a>

          <a href=""><li>shop</li></a>
          
        </ul>

    </header>

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

  header {
    height: 6rem;
    color: rgba(255, 255, 255, 1);
  }

  a {
    text-decoration: none;
    margin-right: 2.5rem;
  }

  header ul li {
    color: black;
    list-style-type: none;
  }

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

</style>
