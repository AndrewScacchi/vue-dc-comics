<template>
    <div id="footer">
      <div id="blue-bar">
        <div class="icons">
          <img src="../../src/assets/img/buy-comics-digital-comics.png" alt=""> 
          <p>DIGITAL COMICS</p>
        </div>
        <div class="icons">
          <img src="../../src/assets/img/buy-comics-merchandise.png" alt=""> 
          <p>DC MERCHANDISE</p>
        </div>
        <div class="icons">
          <img src="../../src/assets/img/buy-comics-subscriptions.png" alt=""> 
          <p>SUBSCRIPTION</p>
        </div>
        <div class="icons">
          <img src="../../src/assets/img/buy-comics-shop-locator.png" alt=""> 
          <p>COMIC SHOP LOCATOR</p>
        </div>
        <div class="icons">
          <img src="../../src/assets/img/buy-dc-power-visa.svg" alt=""> 
          <p>DC POWER VISA</p>
        </div>

      </div>
      <div id="footer-main">
        <div>
          <ul>
            <li class="li-title">DC COMICS</li>
            <li>Characters</li>
            <li>Comics</li>
            <li>Movies</li>
            <li>TV</li>
            <li>Games</li>
            <li>Videos</li>
            <li>News</li>
          </ul>
          <ul>
            <li class="li-title">SHOP</li>
            <li>Shop DC</li>
            <li>Shop DC collectibles</li>
          </ul>
        </div>
        <ul>
          <li class="li-title">DC</li>
          <li>Terms of Use</li>
          <li>Privacy policy(New)</li>
          <li>Ad Choices</li>
          <li>Advertising</li>
          <li>Jobs</li>
          <li>Subscriptions</li>
          <li>Talent Workshops</li>
          <li>CPSC Certificates</li>
          <li>Ratings</li>
          <li>Shop Help</li>
          <li>Contact Us</li>
        </ul>
         <ul>
          <li class="li-title">SITES</li>
          <li>DC</li>
          <li>MAD Magazine</li>
          <li>DC Kids</li>
          <li>DC Universe</li>
          <li>DC Power Visa</li>
        </ul>

      </div>
      <div id="footer-bottom">
        <button class="btn">SIGN UP NOW!</button>
        <div id="footer-social">
          <div>Follow us</div>
          <a href="">
            <img src="../assets/img/footer-facebook.png" alt="">
          </a>
          <a href="">
            <img src="../assets/img/footer-twitter.png" alt="">
          </a>
          <a href="">
            <img src="../assets/img/footer-youtube.png" alt="">
          </a>
          <a href="">
            <img src="../assets/img/footer-pinterest.png" alt="">
          </a>
          <a href="">
            <img src="../assets/img/footer-periscope.png" alt="">
          </a>
        </div>

      </div>
    </div>
</template>

<script>
export default {
  name: 'MyFooter',
}
</script>

<style scoped lang="css">
  #blue-bar {
    display:flex;
    flex-direction: row;
    justify-content: space-around; 
    align-items: center; 
    /* debug */
    background-color: #0282f9;
    height: 100px;
    padding: 15px 15%;
    color: white;

  }
  #blue-bar .icons {
    display: flex;
    flex-direction: row;
    align-items: center;
    gap: 5px;
    font-size: 0.8em;
    min-width: 150px;
  }
  .icons:hover {
    cursor: pointer;
    font-size: 1.05em;
    transform: scale(105%);
  }
  #blue-bar img {
    max-height: 40px;
    max-width: 40px;
  }



  #footer{
    background: url(../assets/img/dc-logo-bg.png),
                url(../assets/img/footer-bg.jpg);
    background-repeat: no-repeat;
    background-position-x: right;
    display: flex;
    flex-direction: column;
    
    height: 500px;
    
  }
  #footer-main {
    color: white;
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
    align-items: left;
    flex-wrap: wrap;
    padding: 15px 15%;
    height: 250px;
    width: 50%
  }
  
  #footer-main ul li{
    list-style: none;
    font-size: 0.65em;
    font-weight: lighter;
  }
  #footer-main .li-title {
    font-weight: bold;
    font-size:1em;
    padding: 0.5em 0;
  }
  #footer-bottom {
    margin-top: auto;
    background-color: #303030;
    width: 100%;
    min-height: 100px;
    padding: 15px 15%;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  #footer-bottom div {
    color: #0282f9;
  }
  #footer-social {
    display: flex;
    align-items: center;
    gap: 10px;
  }
  #footer-social a {
    display: inline-block;
    margin: 5px;
    width: 25px;
  }
  .btn{
    border: 1px solid #0282f9;
    background-color: #303030;
    color: white;
    padding: 0.5em;
    font-size: 0.9em;
  }
  .btn:hover {
    border-color: white;
    background-color: #0282f9;
    cursor: pointer;
  }
</style>