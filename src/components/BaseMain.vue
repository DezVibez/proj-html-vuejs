<template>
<div>
  <div class="meet-section">
    <div class="my-container">
      <div class=" mx-auto pt-5">
  
        <div>
          <h2 class="text-center mb-3 mx-auto">
            <div>
              Meet The New Agency SEO Template 
            </div>
            <div>
              From The Avada Team
            </div>
          </h2>
    
          <p class="text-center mx-auto w-50">
            Lorem ipsum, dolor sit amet consectetur adipisicing elit. Consectetur obcaecati tenetur eius accusamus 
          </p>
        </div>
            
          


        <div class="d-flex justify-content-between mb-5">
          <div class="text-center border p-5  meet-section-card bg-white">
            
          </div>

          <div class="text-center border p-5 meet-section-card bg-white">

          </div>

          <div class="text-center border p-5 meet-section-card bg-white">

          </div>
        </div>

        <div class="my-table">

        </div>

          
      </div>
    </div>

  </div>

  <div class="see-services-section text-white py-5">

    <div class="my-container">

      <div class="text-center mx-auto py-5">
        <h2 class="fw-bold my-3">
          See Our Top Notch Services
        </h2>

        <p class="w-50 mx-auto">
          Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quia sequi hic doloribus ea aut soluta esse aperiam labore deleniti illum? 
        </p>
      </div>

      <div class="service-card-box d-flex justify-content-between pb-5">
        <div class="service-card border p-3">
         Lorem ipsum dolor sit amet, consectetur adipisicing elit. Provident, voluptate sunt! Ea, voluptatum. Ea odit aliquid cupiditate enim iusto eaque 
        </div>
        <div class="service-card border p-3">

        </div>
        <div class="service-card border p-3">

        </div>
        <div class="service-card border p-3">

        </div>
      </div>

    </div>

  </div>

  <div class="our-work py-3">

    <div class="my-container">
      <div class="text-center mx-auto py-5">
        <h2 class="fw-bold my-3">
          Our Work
        </h2>

        <p class="w-50 mx-auto">
          Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quia sequi hic doloribus ea aut soluta esse aperiam labore deleniti illum? 
        </p>
      </div>

      <div class="our-work-card-box d-flex flex-wrap justify-content-between mb-3">
        <div class="our-work-card my-2">
          <img class="img-fluid" src="../assets/images/case-study-gallery-1-1.jpg" alt="">
        </div>
        <div class="our-work-card my-2">
          <img class="img-fluid" src="../assets/images/case-study-gallery-2.jpg" alt="">
        </div>
        <div class="our-work-card my-2">
          <img class="img-fluid" src="../assets/images/case-study-gallery-3-1.jpg" alt="">
        </div>
        <div class="our-work-card my-2">
          <img class="img-fluid" src="../assets/images/case-study-gallery-4-1.jpg" alt="">
        </div>
        <div class="our-work-card my-2">
          <img class="img-fluid" src="../assets/images/case-study-gallery-5-1.jpg" alt="">
        </div>
        <div class="our-work-card my-2">
          <img class="img-fluid" src="../assets/images/case-study-gallery-6-1.jpg" alt="">
        </div>


      </div>

      <div class="d-flex justify-content-center my-5">
        <button class="main-btn fw-bold general-font">
        VIEW OUR WORK
        </button>
      </div>

    </div>

  </div>

  
  
</div>
</template>

<script>
export default {
  name: 'BaseMain',
  props: {
    
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

@import "../assets/sass/vars";

//utils
  .my-container {
    max-width: 70%;
    margin: 0 auto;
  }

//meet-section
.meet-section{
  background-color: $meet_bg;

  .meet-section-card{
  width: 32%;
  }

  .my-table{
    height: 420px;
    background-image: url(../assets/images/agency-seo-desk-front-1200x570.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    background-position-y: -2rem;
  }
}

//see-services-section
.see-services-section{
  
  background-image: url(../assets/images/pattern_background.png);
  background-color: $see_service_bg;
  background-position-x: -3rem;
  background-position-y: -1rem;
  background-repeat: no-repeat;
  background-size: cover;

  .service-card{
    width: 24%;
    background-color: $service_card_bg;
  }
}

//our-work-section
.our-work{
  

  .our-work-card{
    width: 32%;
  }
}
</style>