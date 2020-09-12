<template>
  <!-- <div class="gift">
      <div class="gift-tie-1"></div>
      <div class="gift-tie-2"></div>
      <div class="gift-top"></div>
      <div class="gift-body"></div> -->
  <!-- </div> -->
  <div class="gift">
      <img src="../assets/gift.png" width="80px" height="80px" alt="gift">
  </div>
</template>

<script>
export default {
    name: 'Gift'
}
</script>

<style>
/* .gift {
    position: relative;
    display: flex;
    flex-direction: column;
    align-items: center;
    z-index: 10;
}



.gift-body {
    width: 90px;
    height: 60px;
    background-color: gold;
}

.gift-top {
    width: 100px;
    height: 25px;
    margin-bottom: 1px;
    box-shadow: 0px 1px 0px 0px goldenrod;
    background-color: gold;
}

.gift-tie-1 {
    position: absolute;
    width: 15px;
    height: 85px;
    background-color: red;
}

.gift-tie-2 {
    position: absolute;
    top: 40px;
    width: 90px;
    height: 15px;
    background-color: red;
} */

.gift {
    position: relative;
    display: flex;
    flex-direction: column;
    align-self: flex-end;
    z-index: 1;
    margin-bottom: 10px;
}
</style>