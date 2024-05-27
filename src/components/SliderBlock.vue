<script >
import TheHeader from "@/components/TheHeader.vue";
export default {
  components:{TheHeader}
}

</script>

<template>
<div class="wrapper">
  <div class="slider">
    <TheHeader></TheHeader>
    <div class="slider-main">
      <img src="" alt="arrow">
      <div class="card-buy">
        <h1>Bloodborn <span>TM</span></h1>
        <div class="card-item">
          <div>
          <p>Sony Interactive Entertainment</p>
          <div>PS4</div>
          </div>
          <div class="card-rating">
            <h2>4.73</h2>
            <div class="card-stars">
              <img alt="star">
              <img alt="star">
              <img alt="star">
              <img alt="star">
              <img alt="star">
            </div>
            <p>225.05 rating</p>
          </div>
          <div class="card-buy_select">
            <div class="card_select">$19.99</div>
            <div class="card_select">
              <div>
                <div>
                  <h1>Included</h1>
                  <p>$19.99</p>
                </div>
                <div>
                  <img alt="ps plus">
                  <p>Subscribe to PlayStation Plus Extra to access<br>
                    this game and hundreds more in the Game<br> Catalog</p>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div></div>
      </div>
      <img src="" alt="arrow-right">
    </div>
  </div>
</div>
</template>

<style scoped>
.slider {
  width: 100%;
  background: url("../assets/img/Background_Bloodborn.png") no-repeat;
  height: 50em;
}

.slider-main{
  height: 100%;
  display: flex;
  flex-direction: row;
  border: 1px solid black;
}

</style>