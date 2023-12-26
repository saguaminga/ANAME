<template>
  <div class="CONTENIDO">
    <div class="contenedor-wrapper">
      <div class="contenedor-2">
        <FotosContenido />
        <SeccionDestacada />
        <Encabezado />
        <SeccionCampeonatos />
        <SeccionNoticias />
      </div>
    </div>
  </div>
</template>

<script>
import FotosContenido from "./Contenido/SeccionesContenido/FotosContenido.vue";
import SeccionCampeonatos from "./Contenido/SeccionesContenido/SeccionCampeonatos.vue";
import SeccionDestacada from "./Contenido/SeccionesContenido/SeccionDestacada.vue";
import SeccionNoticias from "./Contenido/SeccionesContenido/SeccionNoticias.vue";

export default {
  name: "Contenido",
  components: {
    FotosContenido,
    SeccionCampeonatos,
    SeccionDestacada,
    SeccionNoticias,
  },
};
</script>


<style>
 .CONTENIDO {
  align-items: center;
  display: flex;
  flex-direction: column;
  left: 0;
  padding: 0px 300px;
  position: absolute;
  top: 711px;
  width: 1920px;
}

.CONTENIDO .contenedor-wrapper {
  align-items: flex-start;
  background-color: #fff2f1;
  display: flex;
  flex: 0 0 auto;
  flex-direction: column;
  max-width: 1320px;
  padding: 0px 12px;
  position: relative;
  width: 1320px;
}

.CONTENIDO .contenedor-2 {
  height: 2701px;
  margin-right: -12px;
  position: relative;
  width: 1308px;
}

</style>