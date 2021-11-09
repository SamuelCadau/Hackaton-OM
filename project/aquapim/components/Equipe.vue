<template>
  <div class="mt-5" id="equipe">
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet" />
    
    <b-container>
      <div class="col-12 mt-4">
      <!-- MODIFICATION TITRE -->
      <p id="title">L'EQUIPE D'AQUAPIM</p>
    </div>
      <b-row class="justify-content-around">
        <div class="col-12 col-sm-12 col-xl-4 col-md-4 mt-4 text-center">
          <h3 class="p-3">Theo</h3>

          <b-img fluid rounded src="../static/pdp.jpg" class="p-3"></b-img>
        </div>

        <div class="col-12 col-sm-12 col-xl-4 col-md-4 mt-4 text-center">
          <h3 class="p-3">Guillaume</h3>

          <b-img fluid rounded src="../static/pdp2.jpg" class="p-3"></b-img>
        </div>
        <div class="col-12 col-sm-12 col-xl-4 col-md-4 mt-4 text-center">
          <h3 class="p-3">Domitille</h3>

          <b-img fluid rounded src="../static/pdp3.jpg" class="p-3"></b-img>
        </div>
      </b-row>
    </b-container>
  </div>
</template>


<script>
AOS.init()
</script>

<script>
export default {}
</script>

<style scoped>
h3 {
  font-family: 'Poppins-Light';

  border-bottom: 3px solid #3e602f;
}

@media all and (min-width: 319px) {
  #title {
    font-size: 8vw;
    font-family: 'Poppins-bold';
    color: #3e602f;
  }
  #equipe {
  margin-top: 15% !important;
}
}

@media all and (min-width: 768px) {
  #title {
    font-size: 3vw;
    font-family: 'Poppins-bold';
    color: #3e602f;
  }
  #equipe {
  margin-top: 10% !important;
}
}
</style>