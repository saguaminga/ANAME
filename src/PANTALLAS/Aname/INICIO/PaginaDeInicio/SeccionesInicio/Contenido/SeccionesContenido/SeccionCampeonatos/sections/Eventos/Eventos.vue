<template>
  <div class="eventos">
    <div class="lista-eventos">
      <EventoA />
      <EventoB />
      <EventoC />
    </div>
  </div>
</template>

<script>
import EventoA from "/seccionesEventos/EventoA.vue";
import EventoB from "/seccionesEventos/EventoB.vue";
import EventoC from "/seccionesEventos/EventoC.vue";

export default {
  name: "Eventos",
  components: {
    EventoA,
    EventoB,
    EventoC,
  },
};
</script>


<style>
.eventos {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  flex-direction: column;
  padding: 0px 0px 20px;
  position: relative;
  width: 100%;
}

.eventos .lista-eventos {
  align-self: stretch;
  height: 860px;
  position: relative;
  width: 100%;
}

</style>