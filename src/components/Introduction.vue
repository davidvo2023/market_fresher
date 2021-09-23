<template>
   <div class="market-introduction">
  <div class=" introduction_image" :style="{backgroundImage:'url('+require('@/assets/images/background_introduction.png')+')'}">
   <div class="introduction_description container_common_normal">
   <h3>What Happened!</h3>
   <p>How to create mobile-optimized videos in minutes. Not a designer,</p>
   <p>every team makes a lot of videos Can be trimmed. Take the first </p>
   <p>step to your brand's success. How to create </p>
   <p>mobile-optimized videos in minutes.</p>
   </div>
   </div>
  
   </div>
</template>

<script>
export default {
  name: 'Introduction',
  props: {
     
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

 .introduction_image {
width: 100%;
    height: 100%;
    background-size: cover;
    background-repeat: no-repeat;
    overflow: hidden;
    background-position: top;
    padding: 0;
}


.introduction_description {
        color: #fff;
   
    display: flex;
    flex-direction: column;
    justify-content: center;
    height: 100%;
}

.introduction_description p {
    padding-bottom: .3vw;
}

.introduction_description h3 {
    margin-bottom: 2vw;
}

@media only screen and (max-width: 600px){
 

.market-introduction {
    height: 90vw;
}


.introduction_description h3 {
    margin-bottom: 6vw;
}

.market-introduction p {
    font-size: 4vw;
    padding-bottom: 1.3vw;
}

.market-introduction h3 {
    text-align: center;
}


}
</style>
