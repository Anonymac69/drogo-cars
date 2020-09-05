<template>
  <div class='footer-wrap'>
    <div class="footer-veil">

      <p class="header-alt">Subscribe to Our NewsLetter</p>
      <hr>

      <div class="feed">
        <input class="feed-mail" type="text" placeholder="Example@gmail.com" />
        <button class="feed-btn">Submit</button>
      </div>

      <div class="social">
        <a href="https://twitter.com/anonymac69"><span uk-icon="icon:twitter; ratio:1.6;" class="icon icon-twitter"></span></a>
        <a href="https://github.com/anonymac69"><span uk-icon="icon:github; ratio:1.5;" class="icon icon-github"></span></a>
        <a href="https://instagram.com/anonymac69"><span uk-icon="icon:linkedin; ratio:1.5;" class="icon icon-linkedin"></span></a>
        <a href="https://dribbble.com/anonymac69"><span uk-icon="icon:dribbble; ratio:1.5;" class="icon icon-dribbble"></span></a>
      </div>

      <p class="copyright">anonymac69 &copy; 2020</p>

    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>

  .copyright {
    color: #fff;
    font-family: 'staatliches', cursive;
    font-size: 14px;
    letter-spacing: 2px;
    margin: 30px auto 10px auto;
    word-spacing: 2px;
  }

  .feed {
    align-items: center;
    display: flex;
    justify-content: center;
    margin: 20px auto;
  }

  .feed-btn, 
  .feed-btn:focus {
    background: #ff4500;
    border-radius: 3px;
    border: none;
    color: #fff;
    font-family: 'staatliches', cursive;
    height: 40px;
    outline: none;
    width: 100px;
  }

  .feed-mail,
  .feed-mail:focus {
    align-items: center;
    background: #fff;
    border: none;
    border-radius: 3px;
    display: flex;
    font-family: 'comfortaa';
    font-size: 13px;
    height: 40px;
    margin: 0 5px;
    padding: 0 10px !important;
    outline: none;
    width: 250px;
  }

  .footer-veil {
    align-items: center;
   background: rgba(0, 0, 0, 0.8);
   display: flex;
   flex-flow: column wrap;
   justify-content: center;
   height: 100%;
   width: 100%;
  }

  .footer-wrap {
    align-items: center;
    background: url('../assets/autocave/05.jpg');
    background-position: left;
    background-repeat: no-repeat;
    background-size: cover;
    display: flex;
    flex-flow: column wrap;
    justify-content: center;
    height: 400px;
  }
  
  .header-alt {
   color: #fff;
   font-family: 'Sacramento', cursive;
   font-size: 30px;
  }

  .icon {
    color: #fff;
    margin: 50px 10px 5px 10px;
    text-decoration: none;
  }

  
  /* Social styles */
  .icon-dribbble {
    transition: color 0.6s;
  }

  .icon-dribbble:hover {
    color: #ea4c89;
  }

  .icon-github {
    transition: color 0.6s;
  }

  .icon-github:hover {
    color: #cccccc;
  }

  .icon-linkedin {
    transition: color 0.6s;
  }

  .icon-linkedin:hover {
    color: #0072b1;
  }

  .icon-mail {
    margin: 0 15px 0 0;
    transition: color 0.6s;
  }

  .icon-mail:hover {
    color: #d4463b;
  }

  .icon-twitter {
    transition: color 0.6s;
  }

  .icon-twitter:hover {
    color: #0099ff;
  }

</style>