<template>
    <div class="col-12" id="concept">
      <div class="col-12 d-flex justify-content-center mt-4 pb-3">
        <!-- MODIFICATION TITRE -->
        <p id="title">NOTRE CONCEPT</p>
      </div>

      <div class="col-10 offset-1 d-flex justify-content-center mt-2">
        <!-- MODIFICATION IMAGE (modifier la destination de l'imgage dans src="") -->
        <img class="img-fluid" src="../static/Concept.png" >
      </div>
    </div>

</template>

<style scoped>

@font-face {
    font-family: "Poppins-bold";
    src: local("Poppins-bold"),     url(../static/font/Poppins-Bold.ttf) format("truetype");
}



@media all and (min-width: 319px) {
  #title {
    font-size: 8vw;
    font-family: 'Poppins-bold';
    color: #3e602f;
  }

  #concept {
  margin-top: 10%;
}
}

@media all and (min-width: 768px) {
  #title {
    font-size: 3vw;
    font-family: 'Poppins-bold';
    color: #3e602f;
  }
  #margtop {
  margin-top: 10%;
}
}

</style>