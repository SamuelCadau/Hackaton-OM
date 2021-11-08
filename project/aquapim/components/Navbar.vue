<!-- Cette page contient le menu de navigation ainsi que son style !-->
<template>
  <div id="navbar">
    <b-navbar toggleable="lg" type="dark" variant="success">
      <b-navbar-brand class="mb-0 ml-1" href="#"> <b-img src="../static/logo1.png"  fluid alt="logo" width="100%" /></b-navbar-brand>
      <b-navbar-toggle target="nav-menu">
      <template #default="{ expanded }">
        <b-icon v-if="expanded" icon="menu-down"></b-icon>
        <b-icon v-else icon="menu-up"></b-icon>
       
      </template>  
      </b-navbar-toggle>
      <b-collapse id="nav-menu" is-nav>
        <b-navbar-nav class="nav mx-auto" right>
          <b-nav-item id="link1">Notre concept</b-nav-item>
          <b-nav-item>Nos partenaires</b-nav-item>
          <b-nav-item>Présentation de l'aquaponie</b-nav-item>
          <b-nav-item>L'équipe</b-nav-item>
          <b-nav-item>Nous rejoindre </b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<style>
@font-face{
    font-family: "Poppins-Medium";
    src:local("Poppins-Medium"), url(../static/Poppins-Medium.ttf) format("truetype");

}

.nav{
  font-family: "Poppins-Medium";
  color:"white";
}

#link1{
    color:"white" !important;
}

</style>