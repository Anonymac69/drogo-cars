<template>
<div class="nav-wrap">
  <div class="nav">
    <div class="brand">
      <nuxt-link class="brand-name" to="/">DRO<span class="dot">G</span>O CARS</nuxt-link>
    </div>

    <div class="links">
      <nuxt-link class="brand-links" to="/">Home</nuxt-link>
      <nuxt-link class="brand-links" to="#about">About</nuxt-link>
      <nuxt-link class="brand-links" to="#Services">Services</nuxt-link>
      <nuxt-link class="brand-links" to="#contact">Contact</nuxt-link>
      <span class="nav-btn" uk-icon="icon: menu; ratio: 1.2" uk-toggle="target: #offcanvas-push"></span>
    </div>


    <div id="offcanvas-push" uk-offcanvas="mode: push; flip: true; overlay: true">
        <div class="uk-offcanvas-bar">
            <button class="uk-offcanvas-close" type="button" uk-close></button>

            <div class="nav-sidebar">
                <ul class="nav-menu-items">
                    <li><a href="index.html">Home</a></li>
                </ul>
            </div>
        </div>
    </div>


  </div>
  </div>
</template>

<style>
  .dot {
    color: #ff4500;
  }

  .brand-links {
    color: #070707;
    font-family: 'Staatliches', cursive;
    font-size: 16px;
    font-weight: 500;
    margin-left: 22px;
    text-decoration: none !important;
    transition: color 0.5s;
  }

  .brand-links:hover {
    color: #ff4500;
  }

  .brand-name, 
  .brand-name:hover {
    color: #070707;
    font-size: 22px;
    font-weight: 500;  
    font-family: 'Staatliches', cursive;
    letter-spacing: 1px;
    text-decoration: none;
  }
  
  .nav {
    align-items: center;
    display: flex;
    flex-flow: row wrap;
    height: 100%;
    justify-content: space-between;
    margin: 0 auto;
    padding: 15px 0;
    max-width: 900px;
  }

  .nav-btn {
    display: none;
    /* padding-top: 3px; */
  }

  .nav-wrap {
    background: #fff;
    flex-basis: 12%;
    width: 100%;
  }





  @media screen and (max-width: 1200px) {
    .brand-links {
      display: none;
    }

    .brand-name {
      margin-left: 20px;
    }
    
    .nav-btn {
      display: flex;
      margin-right: 20px;
    }
  }

  @media screen and (max-width: 800px) {
    .brand-name {
      font-size: 18px;
    }

    .nav {
      
    }

    .nav-wrap {
      flex-basis: 10%;
    }
  }

</style>