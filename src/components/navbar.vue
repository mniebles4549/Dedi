<template>
  <div>
    <b-navbar toggleable="lg" type="dark" variant="info">
      <img src="@/assets/logo-light.png" width="120" alt="Logotipo de Dedi" class="img-fluid" />
<b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav>
          <b-nav-item href="#">Inicio</b-nav-item>
          <b-nav-item href="#" >¿Comó funciona?</b-nav-item>
           <b-nav-item href="#" >Planes</b-nav-item>
            <b-nav-item href="#" >Contacto</b-nav-item>
        </b-navbar-nav>

        <!-- Right aligned nav items -->
        <b-navbar-nav class="ml-auto">
          <b-nav-form>
            <b-button size="sm" class="my-2 my-sm-0 btn btn-danger" type="submit">CONSULTAR MI PEDIDO</b-button>
          </b-nav-form>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

