<template>
  <div class="premium">
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
  .premium {
    /* border: 1px solid red; */
    display: flex;
    flex-direction: column;
    justify-content: center;
    height: 450px;
    margin: 0 auto;
    width: 900px;
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
  }

  .card1, .card2 {
    border-radius: 3px;
    display: flex;
    flex-direction: column-reverse;
    height: 250px;
    justify-content: flex-start;
    margin: 30px 10px;
    width: 430px;
  }

  .card1 {
    background: url('../assets/autocave/35.jpg');
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
  }

  .card-name {
    align-items: center;
    background: #212121;
    border-radius: 0 0 3px 3px;
    color: #fff;
    display: flex;
    font-family: 'staatliches', cursive;
    justify-content: center;
    height: 50px;
    letter-spacing: 2px;
    margin: 0;
  }

  .card2 {
    background: url('../assets/autocave/19.jpg');
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
  }

</style>