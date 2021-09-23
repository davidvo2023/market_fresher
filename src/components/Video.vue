<template>
  <div class="market-video">
    <div class="video__top"
    :style="{
          backgroundImage:
            'url(' + require('@/assets/images/background_video.png') + ')',
        }"
    >
      <div class="video__top_content">
         
        <div class="brand_story__right">
          <h4 class="title_small">what happened</h4>
          <p class="description_small">
          How to create mobile-optimized videos in minutes. Not a designer, 
every team makes a lot of videos Can be trimmed. Take the first 
          </p>
          <button class="button button_video">See more</button>
        </div>
      </div>
    </div>
    
  </div>
</template>

<script>
export default {
  name: "Video",
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
    padding-top: 4.4vw;
}
.video__top {
    background-repeat: no-repeat;
    background-size: cover;
    width: 100%;
    height: 64vw;
    margin-top: 0vw;
    padding-bottom: 3vw;
    cursor: pointer;
}
.video__top_content {
  text-align: center;
}

button.button_video {
  background: #fff;
}

h4.title_small {
  margin-bottom: 2vw;
}

p.description_small {
  width: 61%;
  margin: 0 auto;
  margin-bottom: 3vw;
}

.video__bottom_content {
  background-repeat: no-repeat;
  background-size: contain;
  width: 100%;
  height: 31vw;
  margin-top: 5vw;
  padding-bottom: 3vw;
  cursor: pointer;
}

@media only screen and (max-width: 600px){
 

.video__top {
    width: 100%;
    height: 68vw;
    margin-top: 0vw;
    padding-bottom: 3vw;
    cursor: pointer;
    position: relative;
}

.market-video .brand_story__right {
    width: 92%;
    margin: 0 auto;
    padding-top: 9.4vw;
    position: absolute;
    top: 100%;
    left: 50%;
    transform: translateX(-50%);
    /* height: 50vw; */
    /* margin-bottom: 13vw; */
}

.market-video p.description_small {
    width: 100%;
    margin-bottom: 6vw;
}

.market-video {
    height: 132vw;
}

}
</style>
