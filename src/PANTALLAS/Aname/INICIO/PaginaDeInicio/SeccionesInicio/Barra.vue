<template>
  <div class="overlap">
    <div class="PORTADA">
      <div class="contenedor-portada">
        <div class="carrusel-fotos">
          <div class="presentacion-portada">
            <img class="image-3" alt="Image" src="/img/image-1.png" />
          </div>
          <div class="titulo-pagina">
            <div class="box-titulo-pagina">
              <div class="overlap-group">
                <div class="titulo-pagina-2">
                  <div class="link-2">
                    <div class="text-wrapper-12">ASOCIACIÓN NACIONAL</div>
                    <div class="text-wrapper-13">DE ATLETISMO MASTER</div>
                    <div class="text-wrapper-14">DEL ECUADOR</div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="portada-flecha">
        <div class="span-carousel">
          <div class="symbol"></div>
        </div>
      </div>
      <div class="span-carousel-wrapper">
        <div class="span-carousel">
          <div class="symbol"></div>
        </div>
      </div>
    </div>
    <div class="BARRA-DE-NAVEGACION">
      <div class="contenedor-barra">
        <div class="barra-navegacion">
          <div class="columna-logo">
            <img class="seccion-barra-logo" alt="Seccion barra logo" src="/img/seccionbarralogo.svg" />
          </div>
          <div class="columna-navegacion">
            <div class="menu-navegacion-wrapper">
              <div class="menu-navegacion">
                <div class="lista-navegacion">
                  <div class="div-wrapper-3">
                    <div class="link-inicio">
                      <div class="text-wrapper-15">Inicio</div>
                    </div>
                  </div>
                  <div class="div-wrapper-3">
                    <div class="link-inscripcion">
                      <div class="text-wrapper-15">Inscripción</div>
                      <div class="flecha-inscripcion">
                        <div class="symbol-2"></div>
                      </div>
                    </div>
                  </div>
                  <div class="div-wrapper-3">
                    <div class="link-campeonato">
                      <div class="text-wrapper-16">Campeonato</div>
                      <div class="flecha-campeonato">
                        <div class="symbol-2"></div>
                      </div>
                    </div>
                  </div>
                  <div class="div-wrapper-3">
                    <div class="link-administracion">
                      <div class="text-wrapper-16">Administración</div>
                      <div class="flecha">
                        <div class="symbol-2"></div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="symbol-3"></div>
          </div>
          <div class="div-wrapper-4">
            <div class="div-wrapper-5">
              <div class="boton-login-forma">
                <div class="div-wrapper-6">
                  <div class="div-wrapper-7">
                    <div class="text-wrapper-17">Iniciar Sesión</div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="div-wrapper-4">
            <div class="div-wrapper-5">
              <div class="boton-registro-forma">
                <div class="div-wrapper-6">
                  <div class="div-wrapper-7">
                    <div class="text-wrapper-17">Registrarse</div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Overlap",
};
</script>

<style>
.overlap {
  height: 640px;
  left: 0;
  position: absolute;
  top: 30px;
  width: 1920px;
}

.overlap .PORTADA {
  align-items: flex-start;
  display: flex;
  flex-direction: column;
  height: 628px;
  left: 0;
  position: absolute;
  top: 0;
  width: 1920px;
}

.overlap .contenedor-portada {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  flex-direction: column;
  height: 635px;
  margin-bottom: -7px;
  position: relative;
  width: 100%;
}

.overlap .carrusel-fotos {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  flex-direction: column;
  height: 635px;
  position: relative;
  width: 100%;
}

.overlap .presentacion-portada {
  align-items: flex-start;
  align-self: stretch;
  background-color: #151821;
  display: flex;
  flex-direction: column;
  height: 635px;
  justify-content: center;
  position: relative;
  width: 100%;
}

.overlap .image-3 {
  height: 635px;
  position: relative;
  width: 1920px;
}

.overlap .titulo-pagina {
  align-items: flex-start;
  display: flex;
  flex-direction: column;
  left: 384px;
  padding: 20px 0px 68px;
  position: absolute;
  top: 121px;
  width: 480px;
}

.overlap .box-titulo-pagina {
  align-self: stretch;
  height: 249px;
  position: relative;
  width: 100%;
}

.overlap .overlap-group {
  background-image: url(../../../../../../static/img/fondotitulopagina.svg);
  background-size: 100% 100%;
  height: 624px;
  left: -384px;
  position: relative;
  top: -141px;
  width: 1139px;
}

.overlap .titulo-pagina-2 {
  align-items: flex-start;
  display: flex;
  flex-direction: column;
  left: 384px;
  padding: 7px 111.94px 0px 0px;
  position: relative;
  top: 141px;
  width: 480px;
}

.overlap .link-2 {
  align-items: flex-start;
  display: inline-flex;
  flex-direction: column;
  gap: 12px;
  height: 439px;
  margin-right: -96px;
  padding: 2px 1.06px 3px 0px;
  position: relative;
}

.overlap .text-wrapper-12 {
  color: #ffffff;
  font-family: "Open Sans", Helvetica;
  font-size: 30px;
  font-weight: 700;
  letter-spacing: 2px;
  line-height: 36px;
  margin-top: -1px;
  position: relative;
  white-space: nowrap;
  width: fit-content;
}

.overlap .text-wrapper-13 {
  color: #ffffff;
  font-family: "Open Sans", Helvetica;
  font-size: 30px;
  font-weight: 700;
  height: 52px;
  letter-spacing: 2px;
  line-height: 36px;
  position: relative;
  width: 463px;
}

.overlap .text-wrapper-14 {
  color: #ffffff;
  font-family: "Open Sans", Helvetica;
  font-size: 30px;
  font-weight: 700;
  letter-spacing: 2px;
  line-height: 36px;
  position: relative;
  white-space: nowrap;
  width: fit-content;
}

.overlap .portada-flecha {
  align-items: center;
  display: flex;
  justify-content: center;
  left: 0;
  padding: 264.5px 129.37px 264.5px 129.63px;
  position: absolute;
  top: 0;
  width: 288px;
}

.overlap .span-carousel {
  align-items: center;
  background-color: #151821;
  display: inline-flex;
  flex: 0 0 auto;
  flex-direction: column;
  padding: 29px 10px 28px;
  position: relative;
}

.overlap .symbol {
  color: #ffffff;
  font-family: "Font Awesome 5 Free-Solid", Helvetica;
  font-size: 14px;
  font-weight: 400;
  letter-spacing: 0;
  line-height: 14px;
  margin-top: -1px;
  position: relative;
  text-align: center;
  white-space: nowrap;
  width: fit-content;
}

.overlap .span-carousel-wrapper {
  align-items: center;
  display: flex;
  justify-content: center;
  left: 1632px;
  padding: 264.5px 129.37px 264.5px 129.63px;
  position: absolute;
  top: 0;
  width: 288px;
}

.overlap .BARRA-DE-NAVEGACION {
  align-items: center;
  background-color: #003153;
  display: flex;
  flex-direction: column;
  left: 0;
  position: absolute;
  top: 570px;
  width: 1920px;
}

.overlap .contenedor-barra {
  align-items: flex-start;
  display: flex;
  flex: 0 0 auto;
  flex-direction: column;
  position: relative;
  width: 1920px;
}

.overlap .barra-navegacion {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  flex-wrap: wrap;
  gap: 0px 0px;
  height: 69.59px;
  padding: 0px 0.04px 0px 0px;
  position: relative;
  width: 100%;
}

.overlap .columna-logo {
  height: 69.59px;
  max-width: 1920px;
  position: relative;
  width: 639.98px;
}

.overlap .seccion-barra-logo {
  height: 94px;
  left: 0;
  position: absolute;
  top: -25px;
  width: 640px;
}

.overlap .columna-navegacion {
  align-items: flex-start;
  display: flex;
  flex-direction: column;
  height: 68px;
  max-width: 1920px;
  padding: 0px 549.91px 1.4px 12px;
  position: relative;
  width: 795px;
}

.overlap .menu-navegacion-wrapper {
  align-items: flex-start;
  display: inline-flex;
  flex: 0 0 auto;
  margin-bottom: -1.59px;
  margin-right: -296.98px;
  position: relative;
}

.overlap .menu-navegacion {
  align-items: flex-start;
  background-color: #003153;
  display: inline-flex;
  flex: 0 0 auto;
  flex-direction: column;
  position: relative;
}

.overlap .lista-navegacion {
  align-items: flex-end;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  position: relative;
  width: 100%;
}

.overlap .div-wrapper-3 {
  align-items: flex-start;
  display: inline-flex;
  flex: 0 0 auto;
  max-width: 718.08px;
  position: relative;
}

.overlap .link-inicio {
  align-items: flex-start;
  display: inline-flex;
  flex: 0 0 auto;
  flex-direction: column;
  padding: 24px 26.42px 25.19px 20px;
  position: relative;
}

.overlap .text-wrapper-15 {
  color: #ffffff;
  font-family: "Open Sans", Helvetica;
  font-size: 14px;
  font-weight: 400;
  letter-spacing: 2px;
  line-height: 18.2px;
  margin-top: -1px;
  position: relative;
  white-space: nowrap;
  width: fit-content;
}

.overlap .link-inscripcion {
  align-items: flex-start;
  display: inline-flex;
  flex: 0 0 auto;
  flex-direction: column;
  padding: 24px 26.28px 25.19px 20px;
  position: relative;
}

.overlap .flecha-inscripcion {
  align-items: flex-start;
  display: inline-flex;
  flex-direction: column;
  left: 117px;
  padding: 0px 1.75px 0px 0px;
  position: absolute;
  top: 28px;
}

.overlap .symbol-2 {
  color: #ffffff;
  font-family: "Font Awesome 5 Free-Solid", Helvetica;
  font-size: 14px;
  font-weight: 400;
  letter-spacing: 2px;
  line-height: 14px;
  margin-top: -1px;
  position: relative;
  white-space: nowrap;
  width: fit-content;
}

.overlap .link-campeonato {
  height: 68.19px;
  position: relative;
  width: 189.42px;
}

.overlap .text-wrapper-16 {
  color: #ffffff;
  font-family: "Open Sans", Helvetica;
  font-size: 14px;
  font-weight: 400;
  height: 19px;
  left: 43px;
  letter-spacing: 2px;
  line-height: 18.2px;
  position: absolute;
  top: 23px;
  white-space: nowrap;
}

.overlap .flecha-campeonato {
  align-items: flex-start;
  display: inline-flex;
  flex-direction: column;
  left: 169px;
  padding: 0px 1.75px 0px 0px;
  position: absolute;
  top: 28px;
}

.overlap .link-administracion {
  height: 68.19px;
  position: relative;
  width: 111.95px;
}

.overlap .flecha {
  align-items: flex-start;
  display: inline-flex;
  flex-direction: column;
  height: 14px;
  left: 189px;
  padding: 0px 1.75px 0px 0px;
  position: absolute;
  top: 28px;
}

.overlap .symbol-3 {
  color: #ffffff;
  font-family: "Font Awesome 5 Free-Solid", Helvetica;
  font-size: 14px;
  font-weight: 400;
  letter-spacing: 2px;
  line-height: 14px;
  margin-bottom: -14.59px;
  position: relative;
  white-space: nowrap;
  width: fit-content;
}

.overlap .div-wrapper-4 {
  align-items: center;
  display: flex;
  flex-direction: column;
  justify-content: center;
  padding: 10px;
  position: relative;
  width: 233.09px;
}

.overlap .div-wrapper-5 {
  align-items: center;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  flex-direction: column;
  justify-content: center;
  padding: 0px 192.86px;
  position: relative;
  width: 100%;
}

.overlap .boton-login-forma {
  align-items: flex-start;
  background-color: #d62828f5;
  border-radius: 4px;
  box-shadow: 0px 0px 10px #00000080;
  display: inline-flex;
  flex: 0 0 auto;
  margin-left: -169.45px;
  margin-right: -169.45px;
  padding: 15px 29.28px 15px 30px;
  position: relative;
}

.overlap .div-wrapper-6 {
  align-items: flex-start;
  display: inline-flex;
  flex: 0 0 auto;
  justify-content: center;
  position: relative;
}

.overlap .div-wrapper-7 {
  align-items: center;
  align-self: stretch;
  display: inline-flex;
  flex: 0 0 auto;
  flex-direction: column;
  position: relative;
}

.overlap .text-wrapper-17 {
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

.overlap .boton-registro-forma {
  align-items: flex-start;
  background-color: #d62828f5;
  border-radius: 4px;
  box-shadow: 0px 0px 10px #00000080;
  display: inline-flex;
  flex: 0 0 auto;
  margin-left: -161.45px;
  margin-right: -161.45px;
  padding: 15px 29.28px 15px 30px;
  position: relative;
}

</style>
