<template>
  <div class="market-footer">
    <div class=" footer_top container_common_big">
      <div class="footer_top__left">
      <p><strong>what happened </strong></p>
      <ul>
        <li><a href="">[공지] 개인 정보 처리 방침 변경 사전 안내</a></li>
        <li><a href="">  [공지] 29CM 강남 스토어 영업 종료 </a></li>
        <li><a href="">[공지] 개인 정보 처리 방침 변경 사전 안내</a></li>
        <li><a href="">[공지] iOS 10 이하 버전 지원 중단 안내</a></li>
        <li><a href="">[공지] 개인 정보 처리 방침 변경 사전 안내</a></li>
      </ul>
      </div>
      <div class="footer_top__right">
      <div class="item_top__right">
      <p><strong>about us</strong></p>
      <ul> 
        <li><a href="">회사 소개</a></li>
        <li><a href="">인재 채용</a></li>
        <li><a href="">상시 할인 혜택</a></li> 
      </ul>
      </div>
      <div class="item_top__right">
      <p><strong>my order</strong></p>
      <ul>
        <li><a href="">내 주문 </a></li>
        <li><a href="">주문 배송</a></li>
        <li><a href="">취소 / 교환 / 반품 내역</a></li>
        <li><a href=""> 상품 리뷰 내역</a></li>
        <li><a href="">증빙 서류 발급</a></li>
      </ul>
      </div>
      <div class="item_top__right">
      <p><strong>my account </strong></p>
      <ul>
        <li><a href="">회원 정보 수정 </a></li>
        <li><a href="">회원 등급</a></li>
        <li><a href="">마일리지 현황</a></li>
        <li><a href="">쿠폰</a></li> 
      </ul>
      </div>
      <div class="item_top__right">
      <p><strong>Help </strong></p>
      <ul>
        <li><a href="">1 : 1 상담 내역 </a></li>
        <li><a href="">상품 Q & A 내역</a></li>
        <li><a href="">공지 사항</a></li>
        <li><a href="">자주하는 질문</a></li> 
        <li><a href="">고객의 소리</a></li> 
      </ul>
      </div>
      </div>
    </div>


    <div class=" footer_bottom container_common_big">
      <div class="footer_bottom__left">
      <div class="footer_bottom__left_content">
      <span class="copy_right">© 2020-2021 what happened corp  l  (주) 왓헤픈 ｜ 대표자 : 홍길동 ｜ 사업자 등록번호 : 356-00-00000 ㅣ test0101@what happened.co.kr
서울특별시 강남구 도산대로 8길 17 ｜ FAX : 070-0000-0000  l  서비스 이용약관  l  개인정보처리방침 </span>
      </div>
      </div>
      <div class="footer_bottom__right">
       <div class="footer_bottom__left_content">
       <div class="item_social">
       <a href="">
       <img :src="require('@/assets/images/social1.png')"/>
       </a>
       <a href="">
       <img :src="require('@/assets/images/social2.png')"/>
       </a>
       <a href="">
       <img :src="require('@/assets/images/social3.png')"/>
       </a>
       </div>
      </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Footer",
  props: {},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>


.footer_top {
    display: flex;
    justify-content: space-between;
        border-top: 2px solid #f3f3f3;
    margin-top: 6vw;
    padding-top: 2vw;
}

 

.footer_top__right {
    display: flex;
}

.item_top__right {
    margin-left: 5vw;
}

.market-footer ul li a:hover {
    color: #482ddd;
}


.footer_bottom.container_common_big {
    border-top: 2px solid #f3f3f3;
    display: flex;
    justify-content: space-between;
    padding-top: 1vw;
    margin-top: 4vw;
    padding-bottom: 5vw;
}

.footer_bottom__left {
    /* color: #a9a9a9; */
    width: 53%;
}

.footer_bottom__right {
    width: 30;
}

.item_social a {
    margin-left: 1vw;
}

.footer_top strong {
    margin-bottom: 1vw;
    display: block;
}

@media only screen and (max-width: 600px){
 
.footer_top {
    display: block;
    justify-content: space-between;
    border-top: 2px solid #f3f3f3;
    margin-top: 6vw;
    padding-top: 9vw;
}

ul li a {
    font-size: 3.729vw;
}

.market-footer strong {
    font-size: 4vw;
    padding-bottom: 3vw;
}

.footer_top__right {
    /* display: block; */
    display: grid;
    grid-template-columns: repeat(2,1fr);
    margin-top: 7vw;
    border-top: 2px solid #f3f3f3;
    padding-top: 6vw;
}

.item_top__right {
    margin-left: 0;
    margin-bottom: 9vw;
}

span.copy_right {
    font-size: 3.4vw;
    text-align: center;
    display: block;
}

.footer_bottom.container_common_big {
    border-top: 2px solid #f3f3f3;
    display: block;
    justify-content: space-between;
    padding-top: 6vw;
    margin-top: -1vw;
    padding-bottom: 5vw;
}

.footer_bottom__left {
    width: 100%;
}

.footer_bottom__right {
    text-align: center;
    margin-top: 4vw;
}

.item_social img {
    width: 7vw;
}

.item_social a {
    margin-left: 2vw;
}
}
</style>
