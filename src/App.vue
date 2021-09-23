<template>

  <div class="market">
    <Header />
    <Banner />
    <Introduction />
    <BestProduct />
    <Product />
    <BrandStory />
    <BrandInfo />
    <Video />
    <Footer />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Banner from "./components/Banner.vue";
import Introduction from "./components/Introduction.vue";
import BestProduct from "./components/BestProduct.vue";
import Product from "./components/Product.vue";
import BrandStory from "./components/BrandStory.vue";
import BrandInfo from "./components/BrandInfo.vue";
import Video from "./components/Video.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    Header,
    Banner,
    Introduction,
    BestProduct,
    Product,
    BrandStory,
    BrandInfo,
    Video,
    Footer
  },
  methods: {
 isMobile() {
   if(/Android|webOS|iPhone|iPad|iPod|BlackBerry|IEMobile|Opera Mini/i.test(navigator.userAgent)) {
     return true
   } else {
     return false
   }
 }
}
};
</script>

<style>
* {
  padding: 0;
  margin: 0;
  list-style-type: none;
  text-decoration: none;
}
@font-face {
  font-family: "MontserratBold";
  src: local("Merienda"),
    url(./assets/fonts/Montserrat-ExtraBold.ttf) format("truetype");
}
@font-face {
  font-family: "MontserratMedium";
  src: local("Merienda"),
    url(./assets/fonts/Montserrat-Bold.ttf) format("truetype");
}
@font-face {
  font-family: "Montserrat";
  src: local("Merienda"),
    url(./assets/fonts/Montserrat-Regular.ttf) format("truetype");
}
@font-face {
  font-family: "NotoSansKR";
  src: local("Merienda"),
    url(./assets/fonts/NotoSansKR-Medium.otf) format("truetype");
}
a,
p,
span {
  font-family: "Montserrat";
}
h1,
h2,
h3,
h4,
h5,
strong,
b {
  font-family: "MontserratBold";
}
h3,.title_normal{
      font-size: 2.604vw;
    text-transform: uppercase;
}
p.description_normal,p{
   font-size:1.042vw;
}
b{
  font-size:1.563vw;
}

p.description_small{
      font-size: 0.833vw; 
          line-height: 1.8;
}
h4,.title_small{
 font-size: 2.344vw;
    text-transform: uppercase;
}
h5,.title_xsmall{
 font-size: 1.302vw;
    text-transform: uppercase;
}
 
a.title_product{
   font-size:0.938vw;
  font-family:  MontserratMedium;
  color:#000
}
span.detail_product{
   font-size:0.833vw
}


button,a.button{
   font-size:1.198vw;
    font-family: "MontserratBold";
        background: #fff;
    height: 3.5vw;
    width: 10.6vw;
    text-transform: uppercase;
    display: block;
    margin: 0 auto;
    cursor: pointer;
    border: 2px solid #000;
}

button.button:hover {
    background: #0565bb;
    color: #fff;
    border-color: #0565bb;
}
ul li {
  font-family: "NotoSansKR";
}
ul li a{
  font-size: 0.729vw;
  color:#000;
}

span.copy_right{
  font-size: 0.729vw;
  color: #a9a9a9;
}

.container_common_big{
  width:88.958vw;
  margin:0 auto;
}
.container_common_normal{
  width:81.771vw;
  margin:0 auto;
}


.market-header {
  background: #111111;
  height: 4.167vw;
}


.market-banner {
    background: #ea4913;
    padding: 5vw 0;
    text-align: center;
}

 .market-introduction {
    width: 100%;
    height: 30vw;
  position:relative;
}

.market-best_product {
    background: #fcd22a;
}

.market-product__container{
    display: grid;
    grid-template-columns: repeat(5,1fr);
    column-gap: 1vw;
    row-gap: 3.7vw;
    padding-top:7vw;
    padding-bottom:6vw;
}

.market-product {
    padding-bottom: 7vw;
}

.market-brand_story {
    background: #0565bb;
    width: 100%;
    height: 45vw;
    position: relative;
}

 .market-brand_info {
    background: #fccb05;
}

.market-footer {
    width: 100%;
}


@media only screen and (max-width: 600px) {
    .container_common_big {
        width: 92%;
    }
    h3, .title_normal {
    font-size: 6vw;
}

   p.description_normal, p {
    font-size: 3vw;
}

.container_common_normal {
    width: 92%;
}
h4, .title_small {
    font-size: 6.344vw;
    padding-top: 0;
}

p.description_small {
    font-size: 3.833vw;
}

button, a.button {
    font-size: 4.198vw;
    font-family: "MontserratBold";
    background: #fff;
    height: 12.5vw;
    width: 36.6vw;
    text-transform: uppercase;
    display: block;
    margin: 0 auto;
    cursor: pointer;
    border: 2px solid #000;
}

h5, .title_xsmall {
    font-size: 4.302vw;
}

a.title_product {
    padding-top: 4.2vw;
    padding-bottom: 3.2vw;
    font-size: 4.938vw;
}

span.detail_product {
    font-size: 4.833vw;
}
    }
</style>
 