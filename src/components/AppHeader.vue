<script>

</script>

<template>

    <header class="d-flex justify-content-between align-items-center">

        <div class="logo-container">
            <img src="/public/img/dc-logo.png" alt="logo">
        </div>

        <ul class="text-uppercase m-0 d-flex justify-content-between align-items-center">
        
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
  }

  header ul li {
    color: black;
    list-style-type: none;
  }
</style>