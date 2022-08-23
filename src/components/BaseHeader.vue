<template>
    <div id="jumbo" class="p-3">
      
      
      <div class="my-container">
        
        <!-- NAVBAR -->
        <div class="nav d-flex justify-content-between align-center">
          
          <div class="main-logo">
            <img src="../assets/images/logo_seo_w_1x.png" alt="">
          </div>

          
          <div>

            <ul class="d-flex align-items-center general-font">
              <li class="mx-4" v-for="(listItem, index) in list" :key="index">{{listItem}}</li>
              <button class="main-btn fw-bold">
              GET IN TOUCH NOW
              </button> 
            </ul>
  
            
          </div>

        </div>

        <div class="jumbo-title">

          <h1 class="fw-bold">
            SEM Campaing Made Simple With Avada
          </h1>
          <p class="general-font">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorum commodi id non assumenda consectetur. 
          </p>

          <button class="main-btn me-3 general-font">
            BUY AVADA NOW
          </button>

          <button class="jumbo-btn general-font">
            CONTACT US
          </button>

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
@import "../assets/sass/buttons";

.my-container {
  max-width: 70%;
  margin: 0 auto;
}

#jumbo {
  color: white;
  height: 700px;
  background-repeat: no-repeat;
  background-size: cover;
  background-position-x: -7rem;
  background-image: url("../assets/images/1-hero-image.png");

  li:hover{
    color: $primary_col;
  }
  button{
    border: none;
  }

  .jumbo-title{
    width: 40%;
    position: relative;
    left:0;
    top:10rem;
  }
}
</style>
