<template>
  <div class="contenedor-boton">
    <div class="div-boton-eventos">
      <div class="link-mas-eventos">
        <div class="boton-proximos">
          <div class="texto-boton-eventos">
            <div class="text-wrapper-7">Próximos Eventos</div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ContenedorBoton",
};
</script>

<style>
.contenedor-boton {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  flex-direction: column;
  position: relative;
  width: 100%;
}

.contenedor-boton .div-boton-eventos {
  align-items: center;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  flex-direction: column;
  padding: 0px 423.25px 0px 423.23px;
  position: relative;
  width: 100%;
}

.contenedor-boton .link-mas-eventos {
  align-items: flex-start;
  background-color: #080808f5;
  border-radius: 4px;
  box-shadow: 0px 0px 10px #00000080;
  display: inline-flex;
  flex: 0 0 auto;
  padding: 15px 29.52px 15px 30px;
  position: relative;
}

.contenedor-boton .boton-proximos {
  align-items: flex-start;
  display: inline-flex;
  flex: 0 0 auto;
  justify-content: center;
  position: relative;
}

.contenedor-boton .texto-boton-eventos {
  align-items: center;
  align-self: stretch;
  display: inline-flex;
  flex: 0 0 auto;
  flex-direction: column;
  position: relative;
}

.contenedor-boton .text-wrapper-7 {
  color: #ffffff;
  font-family: "Open Sans", Helvetica;
  font-size: 16px;
  font-weight: 700;
  letter-spacing: 0;
  line-height: 16px;
  margin-top: -1px;
  position: relative;
  text-align: center;
  text-decoration: underline;
  white-space: nowrap;
  width: fit-content;
}
</style>
