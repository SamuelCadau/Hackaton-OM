<template>
  <div class="mt-5">
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet" />
    <div class="col-12 d-flex justify-content-center mt-4">
      <!-- MODIFICATION TITRE -->
      <p id="title">L'EQUIPE</p>
    </div>
    <b-container>
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
</style>