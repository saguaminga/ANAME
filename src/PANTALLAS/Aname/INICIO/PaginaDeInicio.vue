
<template>
  <div class="PAGINA-DE-INICIO">
    <Barra />
    <Contenido />
  </div>
</template>

<script>
import { defineProps } from "vue";
import Barra from "./PaginaDeInicio/SeccionesInicio/Barra.vue";
import Contenido from "./PaginaDeInicio/SeccionesInicio/Contenido.vue";

export default {
  name: "PaginaDeInicio",
  components: {
    Overlap,
    Contenido,
  },
};
</script>


<style>
.PAGINA-DE-INICIO {
  align-self: stretch;
  height: 3411px;
  position: relative;
  width: 100%;
}
</style>