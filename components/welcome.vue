<template>
  <div class="motto">
    <div class="motto-shade">
    <p class="motto-head">Even flying starts on wheels.</p>
    <p class="motto-text">car dealership at its very best, classic yet affordable.</p>
    <button class="btn">Buy a Car</button>
    </div>
  </div>
</template>

<style>
 .btn {
   background: #ff5e23;
   color: #fff;
   font-family: 'staatliches', 'cursive';
   font-size: 16px;
   height: 40px;
   width: 200px;
   word-spacing: 4px;
 }

 .btn:focus,
 .btn:visited {
   border: none !important;
   text-decoration: none !important;
 }

 .btn:hover {
   background: #ff4500;
   color: #fff;
 }

 .motto {
   align-items: center;
   /* border: 1px solid red; */
   display: flex;
   flex-direction: column;
   flex-basis: 90%;
   justify-content: center;
 }

 .motto-head {
   color: #fff;
   font-family: 'sacramento', cursive;
   font-size: 45px;
   margin-bottom: 30px;
 }

 .motto-shade {
   align-items: center;
   background: rgba(0, 0, 0, 0.6);
   display: flex;
   flex-direction: column;
   justify-content: center;
   height: 100%;
   width: 100%;
 }

 .motto-text {
   color: #c0c0c0;
   font-family: 'staatliches', cursive;
   font-size: 14px;
   letter-spacing: 2px;
   word-spacing: 5px;
   margin: -15px auto 40px auto;
 }

 @media screen and (max-width: 800px) {
   .motto-head {
     font-size: 32px;
   }
   .motto-text {
    font-size: 12px;
    letter-spacing: 1px;
    word-spacing: 3px;

   }
 }
</style>