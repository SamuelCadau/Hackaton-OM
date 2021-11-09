<!-- Ce fichier contient le code du bas de page !-->

<template>
  <div>
    <b-container id="footer" fluid>
      <b-row>
        <b-col class="mt-3">
          
          <!-- Emplacement email de contact !-->
          <b-row class="mx-auto"> <b-icon class="mr-2 mt-1" icon="envelope"></b-icon> <span>theophile.gallardo@gmail.com</span> </b-row>
          <!-- Emplacement Numéro de téléphone !-->
          
          <b-row class="mx-auto"><b-icon class="mr-2 mt-1" icon="phone"></b-icon> <span></span>+33613296712</b-row>
        </b-col>

        <b-col class="mt-3"> 
          <b-row> <span class="ml-auto mr-5"> <b-icon icon="building"> </b-icon> AQUAPIM, 69 rue du Rouet, 13008 MARSEILLE </span> </b-row>
          <b-row><p> </p></b-row>
        </b-col>
      </b-row>
      <hr class="solid"/>
      <b-row>
        <span class="mx-auto mb-2">Fait à CODE4MARSEILLE</span>
      </b-row>
    </b-container>
  </div>
</template>


<style scoped>
#footer {
  background-color: rgb(65, 65, 65);
  bottom: 0;
  color: white;
  font-family: 'Poppins-Medium';
}
</style>
