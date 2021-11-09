<template>
  <div class="col-12" id="margtop">
    <div class="col-12 d-flex justify-content-center mt-4 pb-3">
      <!-- MODIFICATION TITRE -->
      <p id="title">NOS PARTENAIRES</p>
    </div>

    <div class="col-12 d-flex justify-content-center mt-4 pb-3">
      <b-card-group deck>
        <!-- MODIFICATION TITRE (title="") | MODIFICATION IMAGE (modifier la destination de l'imgage dans img-src="")-->
        <b-card
          title="Ecole 1" id="titlecard"
          img-src="../static/logo.png"
          img-alt="Image"
          img-top
        >
          <b-card-text id="desccard">
            Description
          </b-card-text>
          <template #footer>
            <div class="text-center">
              <a href="#">Site</a>
            </div>
          </template>
        </b-card>
        
        <!-- MODIFICATION TITRE (title="") | MODIFICATION IMAGE (modifier la destination de l'imgage dans img-src="")-->
        <b-card
          title="Ecole 2" id="titlecard"
          img-src="../static/logo.png"
          img-alt="Image"
          img-top
        >
          <b-card-text id="desccard">
            Description
          </b-card-text>
          <template #footer>
            <div class="text-center">
              <a href="#">Site</a>
            </div>
          </template>
        </b-card>

        <!-- MODIFICATION TITRE (title="") | MODIFICATION IMAGE (modifier la destination de l'imgage dans img-src="")-->
        <b-card
          title="Ecole 3" id="titlecard"
          img-src="../static/logo.png"
          img-alt="Image"
          img-top
        >
          <b-card-text id="desccard">
            Description
          </b-card-text>
          <template #footer>
            <div class="text-center">
              <a href="#">Site</a>
            </div>
          </template>
        </b-card>
      </b-card-group>
    </div>
  </div>
</template>

<style>
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
}

#desccard {
  font-family: 'Poppins-light';
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

  #margtop {
  margin-top: 25%;
}
}

@media all and (min-width: 768px) {
  #title {
    font-size: 4vw;
    font-family: 'Poppins-bold';
    color: #3e602f;
  }

  #margtop {
  margin-top: 15%;
}
}
</style>