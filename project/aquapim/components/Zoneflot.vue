<template>
  <div>
    <b-row align-h="center">
      <b-col id="imgZoneFlot"> </b-col>
      <b-col
        cols="7"
        align-self="center"
        class="text-center ml-auto m-5"
        id="titre"
      >
        <h1 id="h1Div" class="p-4">
          "Il ne s'agit plus seulement d'offrir de l'émerveillement mais des
          solutions concrètes à ceux qui veulent changer leur mode de vie."
        </h1>
      </b-col>
    </b-row>
  </div>
  <!-- <div class="p-5" id="firstDiv">
    <b-container>
      <b-row>
        <b-col md="5" sm="12" cols="12" id="imgZoneFlot">
          <b-img src="../static/zoneflot.jpg" rounded fluid></b-img>
        </b-col>
        <b-col
          md="6"
          sm="12"
          cols="12"
          class="pl-3 p-1"
          offset-xl="1"
          offset-md="1"
          id="titre"
          align-self="center"
        >
          <h4 style="color: white">
            "IL NE S'AGIT PLUS SEULEMENT D'OFFRIR DE L'ÉMERVEILLEMENT MAIS DES
            SOLUTIONS CONCRÈTES À CEUX QUI VEULENT CHANGER LEUR MODE DE VIE".
          </h4>
        </b-col>
      </b-row>
    </b-container>
  </div> -->
</template>

<script>
export default {}
</script>

<style scoped>
@font-face {
  font-family: 'Poppins-Medium';
  src: local('Poppins-Medium'),
    url(../static/Poppins-Medium.ttf) format('truetype');
}
@media screen and (max-width: 425px) {
  #titre {
    margin-top: 30px;
    border-bottom: none !important;
    border-left: none !important;
    border-top: 3px solid #a0ca92;
    text-align: left !important;
  }
  #titre > h4 {
    padding-top: 30px;
  }
}

#firstDiv {
  background-color: #3e602f;
}
#h1Div {
  color: white;
  font-size: 2.2rem;
  backdrop-filter: blur(6px);
  border-radius: 20px;
}

#titre {
  position: absolute;
  z-index: 1000;

  border-radius: 10px;
}

#titre {
  font-family: 'Poppins-Medium';
  /* border-bottom: 3px solid #a0ca92;
  border-left: 2px solid #a0ca92; */
  /*   background-color: rgba(160, 202, 146, 0.9);
 */ /* background-color: rgba(255, 255, 255, 0.8); */
}

#imgZoneFlot {
  background-image: url('../static/zoneflot.jpg');
  height: 900px;
  max-height: 100vh;
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}
</style>