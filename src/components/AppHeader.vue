<script>

</script>

<template>

    <header class="d-flex justify-content-between align-items-center">

        <div class="logo-container">
            <img src="/public/img/dc-logo.png" alt="logo">
        </div>

        <ul class="text-uppercase m-0 d-flex justify-content-between align-items-center">
        
            <li><a href="#">characters</a></li>
            <li><a href="#">comics</a></li>
            <li><a href="#">movies</a></li>
            <li><a href="#">tv</a></li>
            <li><a href="#">games</a></li>
            <li><a href="#">collectibles</a></li>
            <li><a href="#">videos</a></li>
            <li><a href="#">fans</a></li>
            <li><a href="#">news</a></li>
            <li><a href="#">shop</a></li>

        </ul>

    </header>

</template>

<style scoped lang="scss">

  template {
    background-color: rgba(255, 255, 255, 1);
    
  }

  header {
    height: 6rem;
    width: 85%;
    margin: 0 auto;
  }

  .logo-container {
    height: 4rem;
    aspect-ratio: 1 / 1;
  }

  img {
    width: 100%;
  }

  a {
    text-decoration: none;
    margin-right: 2.5rem;
    color: black;
  }

  ul li:hover a{
    color: rgba(2, 130, 249, 1);
    border-bottom: 2px solid rgba(2, 130, 249, 1);
  }

  header ul li {
    color: black;
    list-style-type: none;
   
  }
</style>