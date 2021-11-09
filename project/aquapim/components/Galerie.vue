<template>
  <div id="galerie">
    <div class="mt-5" data-aos="zoom-in-up" data-aos-duration="2350">
      <div class="text-center">
        <p id="title">GALERIE</p>
      </div>
      <b-container>
        <b-row class="mt-5 mb-3">
          <div class="col-xl-4 col-lg-4 col-md-4 col-sm-4 col-12 mb-4">
            <b-img rounded fluid src="../static/2.jpg"></b-img>
          </div>
          <div class="col-xl-4 col-lg-4 col-md-4 col-sm-4 col-12 mb-4">
            <b-img rounded fluid src="../static/4.jpg"></b-img>
          </div>
          <div class="col-xl-4 col-lg-4 col-md-4 col-sm-4 col-12 mb-4">
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
          <div class="col-xl-4 col-lg-4 col-md-4 col-sm-4 col-12 mb-4">
            <b-img rounded fluid src="../static/3.jpg"></b-img>
          </div>
          <div class="col-xl-4 col-lg-4 col-md-4 col-sm-4 col-12 mb-4">
            <b-img rounded fluid src="../static/9.jpg"></b-img>
          </div>
          <div class="col-xl-4 col-lg-4 col-md-4 col-sm-4 col-12 mb-4">
            <b-img rounded fluid src="../static/7.jpg"></b-img>
          </div>
        </b-row>
      </b-container>
    </div>
  </div>
</template>

<script>
import aosMixin from '~/mixins/aos.js'

export default {
  mixins: [aosMixin],
}
</script>

<style scoped>
@media all and (min-width: 319px) {
  #title {
    font-size: 8vw;
    font-family: 'Poppins-bold';
    color: #3e602f;
  }
  #galerie {
    margin-top: 15% !important;
  }
}

@media all and (min-width: 768px) {
  #title {
    font-size: 3vw;
    font-family: 'Poppins-bold';
    color: #3e602f;
  }
  #galerie {
    margin-top: 10% !important;
  }
}

h2 {
  font-family: 'Poppins-Medium';
}
</style>