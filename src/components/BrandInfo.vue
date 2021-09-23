<template>
  <div class="market-brand_info">
    <div class="brand_info__top">
      <div class="brand_info__top_content">
        <div
          class="brand_story__right_img"
          :style="{
            backgroundImage:
              'url(' + require('@/assets/images/shake.png') + ')',
          }"
        ></div>
        <div class="brand_story__right">
          <h4 class="title_small">What Happened’s Brand story</h4>
          <p class="description_small">
            모바일에 최적화된 비디오를 단 몇 분 만에 제작해보세요. 디자이너가
            아니더라도, 모든 팀에서 다듬을 수 있습니다. 브랜드의 성공을 위한 첫
            걸음을 내딛어보세요. 비디오를 단 몇 분 만에 제작해보세요.
          </p>
          <button class="button button_brand_info">See more</button>
        </div>
      </div>
    </div>
    <div class="brand_info__bottom">
      <div
        class="brand_info__bottom_content"
        :style="{
          backgroundImage:
            'url(' + require('@/assets/images/album_prod_news.png') + ')',
        }"
      ></div>
    </div>
  </div>
</template>

<script>
export default {
  name: "BrandInfo",
  props: {},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.brand_story__right_img {
  background-repeat: no-repeat;
  background-size: contain;
  width: 100%;
  background-position-x: 96%;
  padding-top: 4vw;
  transform: translateY(3vw);
  height: 4vw;
  position: absolute;
}

.brand_story__right {
  width: 51%;
  margin: 0 auto;
  padding-top: 5vw;
}

.brand_info__top_content {
  text-align: center;
}

button.button.button_brand_info {
  background: #fcd32a;
}

h4.title_small {
  margin-bottom: 2vw;
}

p.description_small {
  width: 97%;
  margin: 0 auto;
  margin-bottom: 3vw;
}

.brand_info__bottom_content {
  background-repeat: no-repeat;
  background-size: contain;
  width: 100%;
  height: 31vw;
  margin-top: 5vw;
  padding-bottom: 3vw;
  cursor: pointer;
}

@media only screen and (max-width: 600px){
 
.brand_story__right {
    width: 92%;
    margin: 0 auto;
    padding-top: 9vw;
    padding-bottom: 10vw;
}

.brand_info__bottom {
    display: none;
}

.brand_story__right_img {
    height: 14vw;
}

.market-brand_info p.description_small {
    padding-top: 2vw;
    padding-bottom: 2vw;
}
}
</style>
