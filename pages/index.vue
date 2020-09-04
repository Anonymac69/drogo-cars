<template>
    <div class="container">
      <div class="banner">
        <navigation />
        <welcome />
      </div>
      <categories />
      <premium />
      <foot />
    </div>
</template>

<script>
export default {
  
}
</script>

<style>
.container {
  display: flex;
  flex-direction: column;
  margin: 0 auto;
  padding: 0 !important;
  min-height: 100vh;
  display: flex;
  text-align: center;
  min-width: 100vw;
}

.banner {
  background: url('../assets/autocave/01.jpg');
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  display: flex;
  flex-direction: column;
  height: 550px;
  width: 100%;
}
</style>
