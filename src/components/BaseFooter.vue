<template>
  <div class="last-section">

    <div class="little-container border">

      <div class="footer-logo my-4">
        <img class="img-fluid" src="../assets/images/logo_seo_1x.png" alt="">
      </div>

      <ul class="footer-main-list d-flex general-font justify-content-between my-5" >
        <li class="" v-for="(listItem, index) in list" :key="index">{{listItem}}</li>
        <li>Get In Touch Now</li>
      </ul>

      <ul class="d-flex general-font footer-sub-list">
        <li class="border-end px-3">Copyright 2012-2020</li>
        <li class="border-end px-3">Avada Theme by <span class="text-black">ThemeFusion</span></li> 
        <li class="border-end px-3">All Right Reserved</li>
        <li class="px-3">Powered by <span class="text-black">WordPress</span></li>
      </ul>

      <div class="social d-flex">
        <div></div>

      </div>


    </div>

    

    
    
  </div>
</template>

<script>
export default {
  name: 'BaseFooter',
  props: {
    list: Array
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import "../assets/sass/vars";

.last-section{
  height: 300px;

  .footer-main-list{

    .li{
      color:$btn_gray;
    }

    li:hover{
      color: $primary_col;
    }
  }

  .footer-sub-list{
    color:$btn_gray;
  }
  

  .little-container{
    margin: 0 auto;
    max-width: 50%;

    .footer-logo{
      margin: 0 auto;
      width: 150px;
    }
  }
}


</style>