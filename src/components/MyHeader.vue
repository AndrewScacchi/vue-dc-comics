<template>
    <div id="header">
      <!-- logo -->
      <div>
        <a href="#" class="logo-main">
          <img src="../assets/img/dc-logo.png" alt="logo">
        </a>
      </div>

      <!-- nav -->
      <nav>
        <a href="">CHARACTERS</a>
        <a href="">COMICS</a>
        <a href="">MOVIES</a>
        <a href="">TV</a>
        <a href="">GAMES</a>
        <a href="">COLLECTIBLES</a>
        <a href="">VIDEOS</a>
        <a href="">FANS</a>
        <a href="">NEWS</a>
        <a href="">SHOP</a>
      </nav>
        <!-- <h1>Header</h1> -->
    </div>
</template>

<script>
export default {
  name: 'MyHeader',

}
</script>

<style scoped lang="scss">
  #header {
    z-index: 10;
    top: 0;
    background-color: white;
    position: sticky;

    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    
    padding: 0px 15%;
    }
    .logo-main img {
      height: 75px;
    }
    nav a {
      display: inline-block;
      text-decoration: none;
      color: #303030;
      margin-right: 10px;
      height: 100px;
      line-height: 100px;
    }
    nav a:hover {
        color: #0282f9;
        border-bottom: 5px solid #0282f9;
    }
    
  
</style>