<template>
  <div class="about" id="about">
    <p class="header">Who we Are...</p>
    <hr>
    <p class="text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Blanditiis placeat, 
      velit quam voluptatibus cum, minima assumenda culpa vel quis earum, corrupti repellat 
      aspernatur temporibus optio mollitia dolore alias! Tenetur, voluptas aperiam saepe esse 
      libero animi ad iste illum aspernatur ab laborum ipsam alias distinctio dolorum placeat 
      reiciendis laudantium sint nobis!</p>

    <p class="header">Top Featured Rides This Week</p>
    <hr>

    <div class="card-wrap">
      <div class="card1">
        <div class="card-name">Aston Martins</div>
      </div>

      <div class="card2">
        <div class="card-name">BMW</div>
      </div>

    </div>

  </div>
</template>

<script>
export default {

}
</script>

<style>
  .about {
    /* border: 1px solid red; */
    display: flex;
    flex-direction: column;
    justify-content: center;
    min-height: 900px;
    margin: 0 auto;
    max-width: 900px;
  }

  .header {
   color: #212121;
   font-family: 'Sacramento', cursive;
   font-size: 30px;
  }

  hr {
    background: #212121;
    margin: 0 auto;
    width: 70px;
  }

  .card-wrap {
    display: flex;
    flex-flow: row wrap;
    justify-content: space-evenly;
  }

  .card1, .card2 {
    border-radius: 3px;
    display: flex;
    flex-direction: column-reverse;
    height: 250px;
    justify-content: flex-start;
    margin: 30px 10px;
    width: 410px;
  }

  .card1 {
    background: url('../assets/autocave/35.jpg');
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
  }

  .card2 {
    background: url('../assets/autocave/19.jpg');
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
  }

  .card-name {
    align-items: center;
    background: rgba(0, 0, 0, 0.4);
    border-radius: 0 0 3px 3px;
    color: #fff;
    display: flex;
    font-family: 'staatliches', cursive;
    justify-content: center;
    height: 50px;
    letter-spacing: 2px;
    margin: 0;
  }

  .text {
    font-family: 'comfortaa';
    font-size: 14px;
    margin: 20px auto 70px auto;
    width: 80%;
  }

  @media screen and (max-width: 1200px) {
    .about {
      margin: 50px auto;
    }
  }

</style>