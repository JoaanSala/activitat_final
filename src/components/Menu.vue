<template>
  <b-navbar toggleable="md" type="dark" variant="info">
    <b-navbar-brand href="#">
      <img src="../assets/barcelona_logo.png" width="50" height="50" class="d-inline-block align-middle" alt="Kitten">
      FC BARCELONA
    </b-navbar-brand>
    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
      <b-container>
        <b-collapse id="nav-collapse" is-nav>
          <b-navbar-nav>
            <!--
            <b-nav-item :to="{name: 'home'}" exact>Home</b-nav-item>
            <b-nav-item :to="{name: 'contacto'}">Contacto</b-nav-item>
           -->
            <b-nav-item class="nav-link" to="/home">Home</b-nav-item>
            <b-nav-item class="nav-link" to="/plantilla">Plantilla</b-nav-item>
            <!--<b-nav-item class="nav-link" to="/addpersonas">AddPersonas</b-nav-item>
            <b-nav-item class="nav-link" to="/tabla">VerTabla</b-nav-item>
            <b-nav-item class="nav-link" to="/otrapagina">OtraPagina</b-nav-item>-->
            <b-nav-item class="nav-link" to="/videos">Videos</b-nav-item>
          </b-navbar-nav>
        </b-collapse>
      </b-container>
  </b-navbar>
</template>


<script>
export default {


}
</script>


<style scoped>

.router-link-exact-active, .router-link-active {
  background-color: rgb(0, 0, 0);
}
</style>