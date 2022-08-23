<template>
    <div id="jumbo">
      
      <div class="container">

        <div class="row">
          <div class="nav d-flex justify-content-between">
            <div class="main-logo">
              <img src="../assets/images/logo_seo_w_1x.png" alt="">
            </div>
  
            <ul class="d-flex">
              <li class="mx-3" v-for="(listItem, index) in list" :key="index">{{listItem}}</li>
            </ul>
          </div>
          
        </div>

          

      </div>
    </div>
</template>

<script>
export default {
  name: "BaseHeader",
  props: {
    list: Array,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import "../assets/sass/vars";

#jumbo {
  color: $primary_col;
  height: 700px;
  background-repeat: no-repeat;
  background-size: cover;
  background-image: url("../assets/images/1-hero-image.png");
}
</style>
