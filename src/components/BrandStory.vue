<template>
  <div class="market-brand_story">
    <div
      class="brand_story__img"
      :style="{
        backgroundImage:
          'url(' + require('@/assets/images/background_brandstory.png') + ')',
      }"
    >
      <div class="brand_story__content">
        <h4 class="title_small">Brand Story</h4>
        <p class="description_small">
          모바일에 최적화된 비디오를 단 몇 분 만에 제작해보세요. 디자이너가
          아니더라도, 모든 팀에서 다듬을 수 있습니다. 브랜드의 성공을 위한 첫
          걸음을 내딛어보세요. 비디오를 단 몇 분 만에 제작해보세요.
        </p>
        <div class="brand_story__two_column">
          <div
            class="brand_story__left"
            :style="{
              backgroundImage:
                'url(' + require('@/assets/images/brand_left.jpg') + ')',
            }"
          ></div>
          <div class="brand_story__right">
            <h5 class="title_xsmall">What Happened’s Brand story</h5>
            <p class="description_small">
              청춘이 있는 바이며, 말이다. 같지 노년에게서 어디 모래뿐일 무엇을
              풀이 옷을 봄바람이다. 새 천고에 놀이 내는 찾아 창공에 광야에서
              살았으며, 듣는다. 수 있는 긴지라 사는가 낙원을 웅대한 아니다. 내는
              이상 할지라도 피다. 피부가 불러 피고 인간의 타오르고 이성은 끝까지
              칼이다. 쓸쓸한 희망의 못할 것은 목숨을 수 그들을 아름답고 고행을
              끝에 설산에서 황금시대를 이상을 운다.
            </p>
            <button class="button button_brand_story">See more</button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "BrandStory",
  props: {},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.brand_story__img {
  background-repeat: no-repeat;
  background-size: contain;
  width: 100%;
  height: -webkit-fit-content;
  height: -moz-fit-content;
  height: 80%;
}

.brand_story__content {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  width: 100%;
}

h4.title_small {
  color: #fcd32a;
  text-align: center;
  padding-bottom: 1.7vw;
}

.brand_story__content > p.description_small {
  color: #fcd32a;
  text-align: center;
  width: 42%;
  margin: 0 auto;
  padding-bottom: 3.5vw;
}

.brand_story__two_column {
  width: 67%;
  margin: 0 auto;
  background: #fff;
  border: 3px solid #111111;
  border-top: 27px solid #111111;
  position: relative;
  box-sizing: border-box;
  display: flex;
  height: 25vw;
  overflow: hidden;
}

.brand_story__two_column:before {
  position: absolute;
  content: "";
  top: -1.2vw;
  left: 1%;
  width: 98%;
  height: 3px;
  background: #094982;
}

.brand_story__two_column:after {
  position: absolute;
  content: "";

  top: -0.9vw;
  left: 1%;
  width: 98%;
  height: 3px;
  background: #094982;
}

.brand_story__left {
  width: 50%;
  background-repeat: no-repeat;
  background-size: cover;
}

.brand_story__right {
  width: 50%;
  box-sizing: border-box;
  border-left: 2px solid #111111;
  padding: 3.6vw 2vw;
}

h5.title_xsmall {
  padding-bottom: 1.3vw;
}

.brand_story__right p.description_small {
  line-height: 1.8;
  text-align: justify;
}

button.button.button_brand_story {
  margin: inherit;
  margin-top: 2.7vw;
}

@media only screen and (max-width: 600px){
 
.market-brand_story {
    height: 246vw;
}

.brand_story__content > p.description_small {
    width: 92%;
    padding-bottom: 5.5vw;
}


.brand_story__two_column {
    width: 92%;
    margin: 0 auto;
    background: #fff;
    border: 3px solid #111111;
    border-top: 27px solid #111111;
    position: relative;
    box-sizing: border-box;
    display: block;
    height: auto;
    overflow: hidden;
}

.market-brand_story .brand_story__right {
    width: 94%;
    box-sizing: border-box;
    border-left: none;
    padding: 3.6vw 2vw;
    padding-bottom: 8vw;
    margin: 0 auto;
}

.market-brand_story .brand_story__left {
    width: 100%;
    background-repeat: no-repeat;
    background-size: cover;
    height: 64vw;
}



.brand_story__right h5.title_xsmall {
    padding-top: 3vw;
    padding-bottom: 4vw;
}

.brand_story__content {
    padding-top: 28vw;
}

.brand_story__right p.description_small {
    /* width: 90%; */
}

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
}
</style>
