<template>
  <div class="category">
    <div class="item-wrap">
      <button v-for="item in categories" :key='item' class="item"> {{item}} </button>
    </div>
  </div>
</template>

<script>
export default {
  data(){
    return {
      categories: [
        'Cars',
        'SUVs',
        'Off Road Trucks',
        'Motorcycles',
      ]
    }
  }
}
</script>

<style>
  .category {
    border-bottom: 1px solid #e0e0e0;
    display: flex;
    justify-content: center;
    height: 65px;
  }

  .item-wrap {
    align-items: center;
    display: flex;
    justify-content: center;
    padding: 0 5px;
    width: 900px;
  }

  .item {
    align-items: center;
    background: none !important;
    border: none;
    border-radius: 3px;
    display: flex;
    flex: 1 1 20%;
    font-family: 'Staatliches', cursive;
    font-size: 16px;
    justify-content: center;
    height: 90%;
    margin: 0 10px;
    transition: color 0.5s;
    width: 120px;
  }

  .item:hover {
    color: #ff4500;
  }

  .item:focus {
    border: none !important;
    outline: none;
  }

  @media screen and (max-width: 800px) {
    .category {
      display: none;
    }
  }
</style>