<template>
  <div id="partenaires">
  <div data-aos="zoom-in" data-aos-duration="2000" class="col-12">
    <div class="col-12 d-flex justify-content-center mt-4 pb-3">
      <!-- MODIFICATION TITRE -->
      <p id="title">NOS PARTENAIRES</p>
    </div>

    <div id="cardborder" class="col-12 d-flex justify-content-center  justify-content-md-start pb-3">
        <!-- MODIFICATION TITRE (title="") | MODIFICATION IMAGE (modifier la destination de l'imgage dans img-src="")-->
        <div class="row" data-aos="slide-left"
      data-aos-duration="1500">
        <b-card
          title="Epitech" id="titlecard"
          img-src="../static/logo_epitech.png"
          img-alt="Image"
          img-top
          class="text-center col-sm-12 col-md-4 col-lg-4"
        >
          <template #footer>
            <div class="text-center">
              <a href="#">Site</a>
            </div>
          </template>
        </b-card>
        <b-card-text class="col-sm-12 col-md-8 col-lg-8 d-flex align-items-center" id="desccard">
            À travers nos cursus de formation en informatique ou axés digital, les projets innovants de nos étudiant·e·s, les start-ups et entreprises de nos Ancien·ne·s, nos relations avec tout l’univers numérique, l’ensemble de nos initiatives et notre pôle de recherche, Epitech est aujourd’hui au cœur de l’écosystème Tech, de l’énergie et des acteur·rice·s qui font et feront le monde.
        </b-card-text>
      </div>
    </div>
    <div id="cardborder" class="col-12 d-flex  justify-content-center justify-content-md-end   pb-3">
      <!-- MODIFICATION TITRE (title="") | MODIFICATION IMAGE (modifier la destination de l'imgage dans img-src="")-->
      <div class="row" data-aos="slide-right"
      data-aos-duration="1500">
      <b-card-text class="col-sm-12 col-md-8 col-lg-8 d-flex align-items-center orderPartenaire" id="desccard">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatem voluptatibus assumenda deleniti praesentium totam corrupti voluptate consequuntur omnis minima quaerat vero dignissimos odio labore temporibus, quos facere iusto debitis odit?
        </b-card-text>
        <b-card
          title="Ecole 2"
          id="titlecard"
          img-src="../static/logo.png"
          img-alt="Image"
          img-top
          class="text-center col-sm-12 col-md-4 col-lg-4 orderImage"
        >
          <template #footer>
            <div class="text-center">
              <a href="#">Site</a>
            </div>
          </template>
        </b-card>
      </div>
    </div>

    <div id="cardborder" class="col-12 d-flex  justify-content-center  justify-content-md-start  pb-3">
      <!-- MODIFICATION TITRE (title="") | MODIFICATION IMAGE (modifier la destination de l'imgage dans img-src="")-->
      <div class="row"
      data-aos="slide-left"
      data-aos-duration="1500"
      >
        <b-card
          title="Ecole 3"
          id="titlecard"
          img-src="../static/logo.png"
          img-alt="Image"
          img-top
          class="text-center col-sm-12 col-md-4 col-lg-4"
        >
          <template #footer>
            <div class="text-center">
              <a href="#">Site</a>
            </div>
          </template>
        </b-card>
        <b-card-text class="col-sm-12 col-md-8 col-lg-8 d-flex align-items-center" id="desccard">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatem voluptatibus assumenda deleniti praesentium totam corrupti voluptate consequuntur omnis minima quaerat vero dignissimos odio labore temporibus, quos facere iusto debitis odit?
        </b-card-text>
      </div>
    </div>
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
@font-face {
  font-family: 'Poppins-bold';
  src: local('Poppins-bold'),
    url(../static/font/Poppins-Bold.ttf) format('truetype');
}

@font-face {
  font-family: 'Poppins-light';
  src: local('Poppins-light'),
    url(../static/font/Poppins-Light.ttf) format('truetype');
}

#titlecard {
  font-family: 'Poppins-bold';
  padding-right: 0px;
    padding-left: 0px;
}


a {
  font-family: 'Poppins-light';
  color: black;
}

a:hover {
  color: black;
}

h5 {
  font-family: 'Poppins-bold';
}

p {
  font-family: 'Poppins-light';
}

@media all and (min-width: 319px) {
  #title {
    font-size: 8vw;
    font-family: 'Poppins-bold';
    color: #3e602f;
  }

  #partenaires {
    margin-top: 20%;
  }

  
}

@media all and (max-width: 426px) {
  #cardborder {
    margin-top: 100px;
    margin-bottom: 100px;
    text-align: center;
  }
  #desccard {
  font-family: 'Poppins-light';
  font-size: 5vw;
}
.orderPartenaire{
    order: 2;
  }
  .orderImage{
    order: 1;
  }
}

@media all and (min-width: 768px) {
  #title {
    font-size: 3vw;
    font-family: 'Poppins-bold';
    color: #3e602f;
  }
  #partenaires {
  margin-top: 10%;
}
#desccard {
  font-family: 'Poppins-light';
  font-size: 1.5vw;
}
}

#cardborder {
    margin-top: 80px;
  }

</style>