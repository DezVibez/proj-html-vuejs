<template>

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

.meet-section{
  background-color: $meet_bg;
}

.my-container {
  max-width: 70%;
  margin: 0 auto;
}

.meet-section-card{
width: 32%;
}

.my-table{
  height: 420px;
  background-image: url(../assets/images/agency-seo-desk-front-800x380.jpg);
  background-repeat: no-repeat;
  background-size: cover;
  background-position-y: -2rem;
}

</style>