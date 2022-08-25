<template>
  <div class="last-section">

    <div class="little-container border">

      <div class="footer-logo my-4">
        <img class="img-fluid" src="../assets/images/logo_seo_1x.png" alt="">
      </div>

      <ul class="d-flex general-font justify-content-between">
        <li class="" v-for="(listItem, index) in list" :key="index">{{listItem}}</li>
        <li>Get In Touch Now</li>
      </ul>
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

  li{
    color:$btn_gray;
  }

  li:hover{
    color: $primary_col;
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