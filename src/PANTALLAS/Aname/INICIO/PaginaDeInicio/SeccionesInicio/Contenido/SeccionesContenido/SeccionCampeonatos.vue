<template>
  <div class="seccion-campeonatos">
    <div class="campeonatos-wrapper">
      <div class="campeonatos-2">
        <Eventos />
        <ContenedorBoton />
      </div>
    </div>
  </div>
</template>

<script>
import Eventos from "./SeccionCampeonatos/sections/Eventos/Eventos.vue";
import ContenedorBoton from "./SeccionCampeonatos/sections/ContenedorBoton/ContenedorBoton.vue";

export default {
  name: "SeccionCampeonatos",
  components: {
    Eventos,
    ContenedorBoton,
  },
};
</script>


<style>
 .seccion-campeonatos {
  align-items: center;
  display: flex;
  flex-direction: column;
  left: 0;
  padding: 0px 78px;
  position: absolute;
  top: 1210px;
  width: 1308px;
}

.seccion-campeonatos .campeonatos-wrapper {
  align-items: flex-start;
  display: flex;
  flex: 0 0 auto;
  position: relative;
  width: 1140px;
}

.seccion-campeonatos .campeonatos-2 {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  flex: 1;
  flex-direction: column;
  flex-grow: 1;
  gap: 70px;
  padding: 10px;
  position: relative;
}

</style>