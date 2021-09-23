<template>
  <div class="market-banner">
    <h3>Lauching open event!</h3>
    <div
      class="background_banner"
      :style="{backgroundImage: 'url(' + require('@/assets/images/background_top.png') + ')'}"
    ></div>
 
    <div class="progress">
      <p class="progress-border_circle">
      <strong>Lorem ipsum</strong>
      </p>

      <p
        class="progress-arrow"
         :style="{backgroundImage: 'url(' + require('@/assets/images/arrow.png') + ')'}"
      ></p>
      <p class="progress-border_line">
      <strong>Market Lauching!</strong>
      </p>
      <p
        class="progress-arrow"
        :style="{backgroundImage: 'url(' + require('@/assets/images/arrow.png') + ')'}"
      ></p>
      <p class="progress-border_circle">
      <strong>Lorem ipsum</strong>
      </p>
    </div>
  </div>
</template>

<script>
 
export default {
  
  name: "Banner",
  data() {
    return { 
      image_banner :"require('/assets/logo.png')"
    };
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>


.market-banner h3 {
    font-style: italic;
     margin-bottom: .4vw;
    text-transform: uppercase;
}

.background_banner {
    background-size: contain;
    width: 51vw;
    height: 27vw;
    background-repeat: no-repeat;
    margin: 0 auto;
}

.progress {
    display: flex;
    justify-content: center;
    align-items: center;
}

p.progress-border_circle {
    border: 3px solid #000;
    border-radius: 22px;
    padding: 5px 20px;
}

p.progress-arrow {
    background-size: contain;
    background-repeat: no-repeat;
    width: 3vw;
    height: 1.6vw;
    margin: 0 4vw;
}

.progress p {
    text-transform: uppercase;
    
}

p.progress-border_line {
    border-top: 3px solid #000;
    border-bottom: 3px solid #000;
    padding: .4vw 1.5vw;
    width: 7vw;
}

@media only screen and (max-width: 600px) {
  

    .background_banner {
        height: 53vw;
        margin: 0 auto;
        margin-top: 6vw;
        width: 88vw;
    }

 
    .progress {
        width: 92%;
        margin: 0 auto;
    }

    p.progress-border_line {
        padding: 1.4vw 1.5vw;
        width: 17vw;
    }

    p.progress-arrow {
        width: 6vw;
        height: 2.6vw;
        margin: 0 3vw;
    }

    .market-banner {
        padding: 12vw 0;
    }


    }
</style>
