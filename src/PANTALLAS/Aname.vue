<template>
  <div class="aname">
    <PaginaDeInicio />
    <PieDePagina />
  </div>
</template>

<script>
import PaginaDeInicio from "./Aname/INICIO/PaginaDeInicio.vue";
import PieDePagina from "./Aname/INICIO/PieDePagina/PieDePagina.vue";

export default {
  name: "Aname",
  components: {
    PaginaDeInicio,
    PieDePagina,
  },
};
</script>


<style>
 .aname {
  align-items: flex-start;
  background-color: #f2f2f2;
  display: flex;
  flex-direction: column;
  max-width: 1920px;
  min-height: 1080px;
  position: relative;
}

</style>