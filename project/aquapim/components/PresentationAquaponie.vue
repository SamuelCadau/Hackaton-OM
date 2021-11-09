<template>
<div id="aquaponie">
  <b-container class="col-12">
    <b-row class="d-flex justify-content-center mt-3">
      <p id="title" class="">L'AQUAPONIE</p>
    </b-row>

    <b-row class="d-flex justify-content-center schema mt-5">
      <b-col class=" mt-5">
        <div class="col1">
          <span class="ml-2">0 changement d'eau </span>
          <br />
          <span class="ml-2">0 intrant chimique </span>
          <br />
          <span class="ml-2"> Autonomie = Peu d'entretien </span>
        </div>
      </b-col>

      <b-col class="">
        <b-img
          id="schema-gif"
          class="mx-auto"
          src="../static/schema.gif"
          fluid-grow
        />
      </b-col>

      <b-col class=" mt-5">
        <div class="col2">
          <span class="ml-2"> Parlement Européen: </span>
          <br />
          <span >
            "Une des 10 technologies qui pourraient changer nos vies"
          </span>
        </div>
      </b-col>
    </b-row>
  </b-container>
  </div>
</template>

<style>

@media all and (min-width: 319px) {
  #title {
    font-size: 8vw;
    font-family: 'Poppins-bold';
    color: #3e602f;
  }

  #aquaponie {
  margin-top: 20%;
}
}

@media all and (min-width: 768px) {
  #title {
    font-size: 3vw;
    font-family: 'Poppins-bold';
    color: #3e602f;
  }
  #aquaponie {
  margin-top: 10%;
}
}

h1 {
  font-family: 'Poppins-Bold';
  color: #3e602f;
}

.col1 {
  border-left-width: 1;
  border-top-style: groove;
  border-left-style: groove;
}

.col2 {
  border-bottom: groove;
  border-right: groove;
}

.schema {
  font-family: 'Poppins-Medium';
  font-size: 20px;
}

#schema-gif {
  width: 500%;
}
</style>