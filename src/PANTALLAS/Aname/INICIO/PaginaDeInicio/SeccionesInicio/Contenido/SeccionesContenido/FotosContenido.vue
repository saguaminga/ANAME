<template>
  <div class="fotos-contenido">
    <div class="div-elementor">
      <div class="div-elementor-widget">
        <div class="div-elementor-widget-wrapper">
          <div class="image-wrapper">
            <img class="image" alt="Image" src="/img/image-3.png" />
          </div>
        </div>
        <div :class="'lnea-divisora'">
          <div class="span-elementor-wrapper">
            <div class="span-elementor" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "FotosContenido",
};
</script>

<style>
.fotos-contenido {
  align-items: center;
  display: flex;
  flex-direction: column;
  left: 0;
  padding: 0px 78px;
  position: absolute;
  top: 0;
  width: 1308px;
}

.fotos-contenido .div-elementor {
  align-items: flex-start;
  display: flex;
  flex: 0 0 auto;
  max-width: 1140px;
  position: relative;
  width: 1140px;
}

.fotos-contenido .div-elementor-widget {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  flex: 1;
  flex-direction: column;
  flex-grow: 1;
  padding: 10px;
  position: relative;
}

.fotos-contenido .div-elementor-widget-wrapper {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  flex-direction: column;
  max-width: 1140px;
  padding: 0px 0px 20px;
  position: relative;
  width: 100%;
}

.fotos-contenido .image-wrapper {
  align-items: center;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  flex-direction: column;
  justify-content: center;
  position: relative;
  width: 100%;
}

.fotos-contenido .image {
  height: 526.91px;
  position: relative;
  width: 885px;
}

.fotos-contenido .lnea-divisora {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  flex-direction: column;
  position: relative;
  width: 100%;
}

.fotos-contenido .span-elementor-wrapper {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  height: 33px;
  justify-content: center;
  padding: 15px 112px;
  position: relative;
  width: 100%;
}

.fotos-contenido .span-elementor {
  align-self: stretch;
  border-color: #d62828;
  border-top-style: solid;
  border-top-width: 3px;
  position: relative;
  width: 896px;
}
</style>
