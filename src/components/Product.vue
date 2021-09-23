<template>
   <div class="market-product">
      <div class="market-product__container container_common_normal">
        <div class="item_product">
          <a href="">
           <img class="item-product__img" :src="require('@/assets/images/e_pro1.jpg')" />
          </a>
          <a href="" class="title_product">
          
          what happen] How to create 
          
          </a>
          <div class="des_favoriotes">
            <div class="des_favoriotes_left">
            <span class="detail_product">2,500 won</span>
            
          </div>
            <div class="des_favoriotes_right">
             <img class="item-product__img_favorites" :src="require('@/assets/images/favoriotes.png')" />
             <span class="detail_product">4</span>
          </div>
          </div>
        </div>
        <div class="item_product">
          <a href="">
           <img class="item-product__img" :src="require('@/assets/images/e_pro1.jpg')" />
          </a>
          <a href="" class="title_product">
          
          what happen] How to create 
          
          </a>
          <div class="des_favoriotes">
            <div class="des_favoriotes_left">
            <span class="detail_product">2,500 won</span>
            
          </div>
            <div class="des_favoriotes_right">
             <img class="item-product__img_favorites" :src="require('@/assets/images/favoriotes.png')" />
             <span class="detail_product">4</span>
          </div>
          </div>
        </div>
        <div class="item_product">
          <a href="">
           <img class="item-product__img" :src="require('@/assets/images/e_pro1.jpg')" />
          </a>
          <a href="" class="title_product">
          
          what happen] How to create 
          
          </a>
          <div class="des_favoriotes">
            <div class="des_favoriotes_left">
            <span class="detail_product">2,500 won</span>
            
          </div>
            <div class="des_favoriotes_right">
             <img class="item-product__img_favorites" :src="require('@/assets/images/favoriotes.png')" />
             <span class="detail_product">4</span>
          </div>
          </div>
        </div>
        <div class="item_product">
          <a href="">
           <img class="item-product__img" :src="require('@/assets/images/e_pro1.jpg')" />
          </a>
          <a href="" class="title_product">
          
          what happen] How to create 
          
          </a>
          <div class="des_favoriotes">
            <div class="des_favoriotes_left">
            <span class="detail_product">2,500 won</span>
            
          </div>
            <div class="des_favoriotes_right">
             <img class="item-product__img_favorites" :src="require('@/assets/images/favoriotes.png')" />
             <span class="detail_product">4</span>
          </div>
          </div>
        </div>
        <div class="item_product">
          <a href="">
           <img class="item-product__img" :src="require('@/assets/images/e_pro1.jpg')" />
          </a>
          <a href="" class="title_product">
          
          what happen] How to create 
          
          </a>
          <div class="des_favoriotes">
            <div class="des_favoriotes_left">
            <span class="detail_product">2,500 won</span>
            
          </div>
            <div class="des_favoriotes_right">
             <img class="item-product__img_favorites" :src="require('@/assets/images/favoriotes.png')" />
             <span class="detail_product">4</span>
          </div>
          </div>
        </div>
        <div class="item_product">
          <a href="">
           <img class="item-product__img" :src="require('@/assets/images/e_pro1.jpg')" />
          </a>
          <a href="" class="title_product">
          
          what happen] How to create 
          
          </a>
          <div class="des_favoriotes">
            <div class="des_favoriotes_left">
            <span class="detail_product">2,500 won</span>
            
          </div>
            <div class="des_favoriotes_right">
             <img class="item-product__img_favorites" :src="require('@/assets/images/favoriotes.png')" />
             <span class="detail_product">4</span>
          </div>
          </div>
        </div>
      </div>
      <button class="button">See more</button>
   </div>
</template>

<script>
export default {
  name: 'Product',
  props: {
     
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
 

.item_product a {
    display: block;
}

.item_product img.item-product__img {
    width: 100%;
    height: 16vw;
}

.des_favoriotes {
    display: flex;
    justify-content: space-between;
}

a.title_product {
    padding-top: 1.2vw;
    padding-bottom: 1.2vw;
}

.des_favoriotes_right {
    display: flex;
    align-items: center;
    cursor: pointer;
}

.des_favoriotes_right img {
    margin-right: 3px;
    width: 1vw;
}

@media only screen and (max-width: 600px){

 
.market-product__container {
    display: block;
}

.item_product img.item-product__img {
    height: 67vw;
}



.des_favoriotes_right img {
    margin-right: 7px;
    width: 6vw;
}

.item_product {
    margin-bottom: 8vw;
}

}
</style>
