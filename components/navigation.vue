<template>
<div class="nav-wrap">
  <div class="nav">
    <div>
      <nuxt-link class="brand-name" to="/">DRO<span class="dot">G</span>O CARS</nuxt-link>
    </div>

    <div class="">
      <nuxt-link class="brand-links" to="/">Home</nuxt-link>
      <nuxt-link class="brand-links" to="#about">About</nuxt-link>
      <nuxt-link class="brand-links" to="#Services">Services</nuxt-link>
      <nuxt-link class="brand-links" to="#contact">Contact</nuxt-link>
    </div>



  </div>
  </div>
</template>

<style>
  .dot {
    color: #ff4500;
  }

  .nav {
    align-items: baseline;
    display: flex;
    height: 100%;
    justify-content: space-between;
    margin: 0 auto;
    padding: 15px 0;
    width: 900px;
  }

  .nav-wrap {
    background: #fff;
    flex-basis: 12%;
    width: 100%;
  }

  .brand-links {
    color: #070707 !important;
    font-family: 'Staatliches', cursive;
    font-size: 16px;
    font-weight: 500;
    margin-left: 20px;
    text-decoration: none !important;
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

</style>