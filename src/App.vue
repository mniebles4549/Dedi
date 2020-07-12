<template>
  <div id="app">
    <navbar />
    <inicio />
    <comofunciona />
    <planes/>
    <contacto />
    <fluter />
  </div>
</template>

<script>

import navbar from "./components/navbar.vue";
import inicio from "./components/inicio.vue";
import comofunciona from "./components/comofunciona.vue";
import planes from "./components/planes.vue";
import contacto from "./components/contacto.vue";
import fluter from "./components/fluter.vue";

export default {
  name: "App",
  components: {
    navbar,
    inicio,
    comofunciona,
    planes,
    contacto,
    fluter
  }
};
</script>

