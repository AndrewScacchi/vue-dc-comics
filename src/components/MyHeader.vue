<template>
    <div id="header">
      <!-- logo -->
      <div>
        <img src="../assets/img/dc-logo.png" alt="logo">
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
  name: 'MyHeader'
}
</script>

<style scoped lang="css">
  #header {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    padding-top: 10px;
    padding-bottom: 10px;
    padding-left: 10%;
    padding-right: 10%;
    }
    a {
      text-decoration: none;
      color: #303030;
      margin-right: 10px;
    }
    a:hover {
        color: #0282f9;
    }
    
  
</style>