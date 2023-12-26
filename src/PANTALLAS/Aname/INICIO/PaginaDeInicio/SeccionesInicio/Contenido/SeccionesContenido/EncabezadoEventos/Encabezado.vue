<template>
  <div class="encabezado">
    <div class="contenedor">
      <div class="campeonatos">
        <div class="div-wrapper-2">
          <div class="text-wrapper-8">PRÓXIMOS CAMPEONATOS</div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Encabezado",
};
</script>


<style>
 .encabezado {
  align-items: center;
  display: flex;
  flex-direction: column;
  left: 0;
  padding: 0px 78px;
  position: absolute;
  top: 1120px;
  width: 1308px;
}

.encabezado .contenedor {
  align-items: flex-start;
  display: flex;
  flex: 0 0 auto;
  max-width: 1140px;
  padding: 10px;
  position: relative;
  width: 1140px;
}

.encabezado .campeonatos {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  flex: 1;
  flex-direction: column;
  flex-grow: 1;
  position: relative;
}

.encabezado .div-wrapper-2 {
  align-items: center;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  flex-direction: column;
  padding: 0px 264.91px 0px 265.09px;
  position: relative;
  width: 100%;
}

.encabezado .text-wrapper-8 {
  color: #151821;
  font-family: "Open Sans", Helvetica;
  font-size: 40px;
  font-weight: 400;
  letter-spacing: 2px;
  line-height: 40px;
  margin-top: -1px;
  position: relative;
  text-align: center;
  white-space: nowrap;
  width: fit-content;
}

</style>
