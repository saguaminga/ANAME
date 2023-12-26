<template>
  <div class="PIE-DE-PAGINA">
    <div class="barra-links">
      <div class="contenedor-links">
        <div class="fila-contenedor">
          <div class="columna-a-links">
            <div class="div-4">
              <div class="encabezado-columna-a">
                <div class="text-wrapper-18">CONTACTO</div>
              </div>
              <div class="texto-columna-a">
                <p class="calle-principal">
                  Calle principal, #, Calle Secundaria
                  <br />
                  Sector
                  <br />
                  Ciudad
                </p>
                <div class="text-wrapper-19">correo@dominio.com</div>
              </div>
            </div>
          </div>
          <div class="columna-b-links">
            <div class="div-4">
              <div class="encabezado-columna-b">
                <div class="text-wrapper-20">INFORMACIÓN</div>
              </div>
              <div class="texto-columna-b">
                <div class="text-wrapper-21">Preguntas frecuentes</div>
                <div class="text-wrapper-19">Próximos Campeonatos</div>
                <a
                  class="link-fednacatletismo"
                  href="https://www.featle.org.ec/"
                  rel="noopener noreferrer"
                  target="_blank"
                >
                  Federación Ecuatoriana de Atletismo
                </a>
                <a class="text-wrapper-19" href="https://asudama.org/" rel="noopener noreferrer" target="_blank">
                  ASUDAMA
                </a>
              </div>
            </div>
          </div>
          <div class="columna-c-links">
            <div class="div-4">
              <div class="encabezado-columna-c">
                <div class="documentos">DOCUMENTOS</div>
              </div>
              <div class="texto-columna-c">
                <div class="text-wrapper-21">Reglamento</div>
                <div class="text-wrapper-19">Categorías</div>
                <div class="text-wrapper-19">Reglas de Campeonatos Pasados</div>
              </div>
            </div>
          </div>
          <div class="columna-d-links">
            <div class="columna-d">
              <div class="encabezado-columna-d">
                <div class="redes-sociales">REDES SOCIALES</div>
              </div>
              <div class="link-facebook">
                <a
                  class="link-facebookaname"
                  href="https://www.facebook.com/profile.php?id=100064841912450"
                  rel="noopener noreferrer"
                  target="_blank"
                >
                  Facebook ANAME
                </a>
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
  name: "PieDePagina",
};
</script>

<style>
.PIE-DE-PAGINA {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  flex-direction: column;
  position: relative;
  width: 100%;
}

.PIE-DE-PAGINA .barra-links {
  align-items: center;
  align-self: stretch;
  background-color: #151821;
  display: flex;
  flex: 0 0 auto;
  flex-direction: column;
  padding: 0px 300px;
  position: relative;
  width: 100%;
}

.PIE-DE-PAGINA .contenedor-links {
  align-items: flex-start;
  display: flex;
  flex: 0 0 auto;
  flex-direction: column;
  max-width: 1320px;
  position: relative;
  width: 1320px;
}

.PIE-DE-PAGINA .fila-contenedor {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  flex-wrap: wrap;
  gap: 0px 0px;
  height: 290px;
  position: relative;
  width: 100%;
}

.PIE-DE-PAGINA .columna-a-links {
  align-items: flex-start;
  display: flex;
  flex-direction: column;
  height: 290px;
  max-width: 1320px;
  padding: 25px 12px 94px;
  position: relative;
  width: 330px;
}

.PIE-DE-PAGINA .div-4 {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  flex-direction: column;
  gap: 8px;
  padding: 16px 0px;
  position: relative;
  width: 100%;
}

.PIE-DE-PAGINA .encabezado-columna-a {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  flex-direction: column;
  padding: 8px 151px 8px 0px;
  position: relative;
  width: 100%;
}

.PIE-DE-PAGINA .text-wrapper-18 {
  color: #ffffff;
  font-family: "Anton", Helvetica;
  font-size: 25px;
  font-weight: 400;
  letter-spacing: 2px;
  line-height: 30px;
  margin-top: -1px;
  position: relative;
  white-space: nowrap;
  width: fit-content;
}

.PIE-DE-PAGINA .texto-columna-a {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  flex-direction: column;
  padding: 0px 72px 1px 0px;
  position: relative;
  width: 100%;
}

.PIE-DE-PAGINA .calle-principal {
  color: #ffffff;
  font-family: "Roboto", Helvetica;
  font-size: 14px;
  font-weight: 400;
  letter-spacing: 0;
  line-height: 21px;
  margin-top: -1px;
  position: relative;
  width: fit-content;
}

.PIE-DE-PAGINA .text-wrapper-19 {
  color: #efca08;
  font-family: "Open Sans", Helvetica;
  font-size: 14px;
  font-weight: 700;
  letter-spacing: 0;
  line-height: 21px;
  position: relative;
  text-decoration: underline;
  white-space: nowrap;
  width: fit-content;
}

.PIE-DE-PAGINA .columna-b-links {
  align-items: flex-start;
  display: flex;
  flex-direction: column;
  height: 290px;
  max-width: 1320px;
  padding: 25px 12px;
  position: relative;
  width: 330px;
}

.PIE-DE-PAGINA .encabezado-columna-b {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  flex-direction: column;
  padding: 8px 259px 8px 0px;
  position: relative;
  width: 100%;
}

.PIE-DE-PAGINA .text-wrapper-20 {
  color: #ffffff;
  font-family: "Anton", Helvetica;
  font-size: 25px;
  font-weight: 400;
  letter-spacing: 2px;
  line-height: 30px;
  margin-right: -99px;
  margin-top: -1px;
  position: relative;
  white-space: nowrap;
  width: fit-content;
}

.PIE-DE-PAGINA .texto-columna-b {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  flex-direction: column;
  gap: 1px;
  padding: 0px 112px 1px 0px;
  position: relative;
  width: 100%;
}

.PIE-DE-PAGINA .text-wrapper-21 {
  color: #efca08;
  font-family: "Open Sans", Helvetica;
  font-size: 14px;
  font-weight: 700;
  letter-spacing: 0;
  line-height: 21px;
  margin-top: -1px;
  position: relative;
  text-decoration: underline;
  white-space: nowrap;
  width: fit-content;
}

.PIE-DE-PAGINA .link-fednacatletismo {
  color: #efca08;
  font-family: "Open Sans", Helvetica;
  font-size: 14px;
  font-weight: 700;
  letter-spacing: 0;
  line-height: 21px;
  margin-right: -64px;
  position: relative;
  text-decoration: underline;
  white-space: nowrap;
  width: fit-content;
}

.PIE-DE-PAGINA .columna-c-links {
  align-items: flex-start;
  display: flex;
  flex-direction: column;
  height: 290px;
  max-width: 1320px;
  padding: 25px 12px 69px;
  position: relative;
  width: 330px;
}

.PIE-DE-PAGINA .encabezado-columna-c {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  flex-direction: column;
  padding: 8px 178px 8px 0px;
  position: relative;
  width: 100%;
}

.PIE-DE-PAGINA .documentos {
  color: #ffffff;
  font-family: "Anton", Helvetica;
  font-size: 25px;
  font-weight: 400;
  letter-spacing: 2px;
  line-height: 30px;
  margin-right: -14px;
  margin-top: -1px;
  position: relative;
  white-space: nowrap;
  width: fit-content;
}

.PIE-DE-PAGINA .texto-columna-c {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  flex-direction: column;
  gap: 1px;
  padding: 0px 76px 1px 0px;
  position: relative;
  width: 100%;
}

.PIE-DE-PAGINA .columna-d-links {
  align-items: flex-start;
  display: flex;
  flex-direction: column;
  height: 290px;
  max-width: 1320px;
  padding: 25px 12px 168px;
  position: relative;
  width: 330px;
}

.PIE-DE-PAGINA .columna-d {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  flex-direction: column;
  gap: 8px;
  margin-bottom: -3px;
  position: relative;
  width: 100%;
}

.PIE-DE-PAGINA .encabezado-columna-d {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  flex-direction: column;
  padding: 16px 188px 16px 0px;
  position: relative;
  width: 100%;
}

.PIE-DE-PAGINA .redes-sociales {
  color: #ffffff;
  font-family: "Anton", Helvetica;
  font-size: 25px;
  font-weight: 400;
  letter-spacing: 2px;
  line-height: 30px;
  margin-right: -56px;
  margin-top: -1px;
  position: relative;
  white-space: nowrap;
  width: fit-content;
}

.PIE-DE-PAGINA .link-facebook {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  flex-direction: column;
  padding: 4px 276px 5px 12px;
  position: relative;
  width: 100%;
}

.PIE-DE-PAGINA .link-facebookaname {
  color: #efca08;
  font-family: "Open Sans", Helvetica;
  font-size: 14px;
  font-weight: 700;
  height: 21px;
  letter-spacing: 0;
  line-height: 21px;
  margin-right: -108px;
  margin-top: -1px;
  position: relative;
  text-decoration: underline;
  white-space: nowrap;
  width: 126px;
}

</style>
