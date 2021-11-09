<template>
  <div class="mt-5">
    <div class="text-center">
      <h2>Galerie</h2>
    </div>
    <b-container>
      <b-row class="mt-3 mb-3">
        <div class="col-xl-4">
          <b-img rounded fluid src="../static/2.jpg"></b-img>
        </div>
        <div class="col-xl-4">
          <b-img rounded fluid src="../static/4.jpg"></b-img>
        </div>
        <div class="col-xl-4">
          <b-img rounded fluid src="../static/5.jpg"></b-img>
        </div>
      </b-row>

      <b-carousel
        id="carousel-fade"
        style="text-shadow: 0px 0px 2px #000"
        fade
        indicators
        img-width="1024"
        img-height="480"
      >
        <b-carousel-slide img-src="../static/6.jpg"></b-carousel-slide>
        <b-carousel-slide fluid img-src="../static/8.jpg"></b-carousel-slide>
        <b-carousel-slide img-src="../static/1.jpg"></b-carousel-slide>
      </b-carousel>
      <b-row class="mt-3 mb-3">
        <div class="col-xl-4">
          <b-img rounded fluid src="../static/3.jpg"></b-img>
        </div>
        <div class="col-xl-4">
          <b-img rounded fluid src="../static/9.jpg"></b-img>
        </div>
        <div class="col-xl-4">
          <b-img rounded fluid src="../static/7.jpg"></b-img>
        </div>
      </b-row>
    </b-container>
  </div>
</template>

<script>
export default {
}
</script>

<style scoped>
h2 {
  font-family: 'Poppins-Medium';
}
</style>