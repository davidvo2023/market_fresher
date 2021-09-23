<template>
  <div class="market-header">
    <div class="container_header container_common_big">
      <div class="container_header_left">
        <a href=""><strong>What happened</strong></a>
      </div>
      <div class="container_header_right">
        <ul>
          <li>
            <a href=""> Introduction</a>
          </li>
          <li>
            <a href=""> Solution</a>
          </li>
          <li class="border_right">
            <a href=""> Rate Plan</a>
          </li>
          <li>
            <a href=""> Login</a>
          </li>
          <li>
            <a href=""> Apply for free use</a>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Header",
  props: {},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>


.container_header {
  display: flex;
  justify-content: space-between;
  height: 100%;
  align-items: center;
}

.container_header a {
  color: #fff;
}

.container_header_right ul {
  display: flex;
}

.container_header_left strong {
  font-size: 20px;
}

.container_header_right a {
  text-transform: uppercase;
}

.container_header_right ul li.border_right {
  border-left: 1px solid #fff;
  padding-left: 38px;
  margin-left: 55px;
}

.container_header_right ul li {
  margin-left: 33px;
  padding-left: 20px;
}


@media only screen and (max-width: 600px) {
   

    .market-header {
        height: 14vw;
    }

    .container_header_right {
        display: none;
    }
     

    }
</style>
