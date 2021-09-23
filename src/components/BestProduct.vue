<template>
  <div class="market-best_product">
    <div class="best_product  ">
      <div class="best_product__top">
        <h4 class="title_small">Best Product</h4>
        <p class="description_small">
          How to create mobile-optimized videos in minutes. Not a designer,
          <br />
          every team makes a lot of videos Can be trimmed. Take the first
        </p>
      </div>
      <div
        class="best_product__bottom "
        :style="{ backgroundImage:'url(' + require('@/assets/images/background_prod.png') + ')'}"
      >
        <div class="best_product__bottom-content container_common_normal">
          <div class="item-best_product">
            <a href="">
              <div class="item-best_product__stt"
               :style="{ backgroundImage:'url(' + require('@/assets/images/sale_best.png') + ')'}"
              ><strong>01</strong></div>
              <img class="item-best_product__img" :src="require('@/assets/images/best_pro1.jpg')" />
               <div class="item-best_product__link">
                <div class="item-best_product__link-left">
             <strong>  How to create mobile-optimized</strong>
               </div> 
                <div class="item-best_product__link-right">
                <strong>go</strong>
               </div> 
             </div> 
            </a>
          </div>
          <div class="item-best_product">
            <a href="">
              <div class="item-best_product__stt"
               :style="{ backgroundImage:'url(' + require('@/assets/images/sale_best.png') + ')'}"
              ><strong>01</strong></div>
              <img class="item-best_product__img" :src="require('@/assets/images/best_pro2.jpg')" />
               <div class="item-best_product__link">
                <div class="item-best_product__link-left">
             <strong>  How to create mobile-optimized</strong>
               </div> 
                <div class="item-best_product__link-right">
                <strong>go</strong>
               </div> 
             </div> 
            </a>
          </div>
          <div class="item-best_product">
            <a href="">
              <div class="item-best_product__stt"
               :style="{ backgroundImage:'url(' + require('@/assets/images/sale_best.png') + ')'}"
              ><strong>01</strong></div>
              <img class="item-best_product__img" :src="require('@/assets/images/best_pro3.jpg')" />
               <div class="item-best_product__link">
                <div class="item-best_product__link-left">
             <strong>  How to create mobile-optimized</strong>
               </div> 
                <div class="item-best_product__link-right">
                <strong>go</strong>
               </div> 
             </div> 
            </a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "BestProduct",
  props: {},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.best_product__top {
  text-align: center;
}

.best_product__top h4 {
  color: #f96400;
  margin-bottom: 1.7vw;
  padding-top: 5vw;
}

p.description_small {
  color: #f96400;
}

.best_product__bottom {
    background-repeat: no-repeat;
    background-size: cover;
    width: 100%;
    height: fit-content;
    padding-bottom: 8vw;
}

.best_product__bottom-content {
    display: grid;
    margin-top: 4vw;
    grid-template-columns: repeat(3,1fr);
        transform: translateY(.5vw);
}

.item-best_product a {
    display: block;
    position: relative;
}

.item-best_product img {
    width: 100%;
    height: 26vw;
}

.item-best_product__stt {
    position: absolute;
    background-repeat: no-repeat;
    background-size: contain;
    width: 5vw;
    height: 5vw;
    line-height: 5vw;
    text-align: center;
    top: -2.5vw;
}

.item-best_product__stt strong {
    /* font-size: 1.563vw; */
    color: #000;
    position: relative;
}

.item-best_product__stt strong:before {content: '';position: absolute;bottom: 1px;left: 0;width: 100%;height: 1px;background: #000;}

.item-best_product__link {
    border: 2px solid #000;
    background: #fff;
    color: #000;
    display: flex;
    justify-content: space-between;
    padding: .4vw .5vw;
    padding-left: 1vw;
    align-items: center;
    /* line-height: 4vw; */
    position: absolute;
    /* margin-top: 2vw; */
    left: 50%;
    bottom: -5%;
    transform: translateX(-50%);
    width: 70%;
}

.item-best_product__link-left {
    width: 64%;
}

.item-best_product__link-right {
    background: #000;
    border-radius: 50%;
    width: 3vw;
    height: 3vw;
    text-align: center;
    line-height: 3vw;
}

.item-best_product__link-right strong {
    color: #fff;
}

@media only screen and (max-width: 600px){

 


.best_product {
    /* width: 92%; */
    /* margin: 0 auto; */
}

.best_product__top {
    width: 92%;
    margin: 0 auto;
}

.best_product__bottom-content.container_common_normal {
    display: block;
    margin-top: 9vw;
}

.item-best_product img {
    height: 80vw;
}

.item-best_product {
    margin-bottom: 17vw;
}

.item-best_product__stt {
    position: absolute;
    background-repeat: no-repeat;
    background-size: contain;
    width: 19vw;
    height: 19vw;
    line-height: 19vw;
    text-align: center;
    top: 0.5vw;
}

.item-best_product__stt strong {
    font-size: 6vw;
}

.item-best_product__link {
    border: 2px solid #000;
    background: #fff;
    color: #000;
    display: flex;
    justify-content: space-between;
    padding: 1.4vw 2.5vw;
    padding-left: 3vw;
    align-items: center;
    /* line-height: 4vw; */
    position: absolute;
    /* margin-top: 2vw; */
    left: 50%;
    bottom: -7%;
    transform: translateX(-50%);
    width: 80%;
}

.item-best_product__link-right {
    background: #000;
    border-radius: 50%;
    width: 10vw;
    height: 10vw;
    text-align: center;
    line-height: 10vw;
}

}
</style>
