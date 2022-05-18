<template lang="pug">
.curso-main-container.pb-3.sintesis
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    p.mb-5(data-aos="fade-left") Se ha llegado al final del componente, en el cual se abordaron temas relacionados con la importancia de los procesos forenses, el manejo de evidencias y el procedimiento que se debe llevar a cabo por parte del personal técnico para garantizar la calidad e integridad de las mismas. También se trataron temáticas relacionadas con las certificaciones de la seguridad de la información y su importancia actual para las organizaciones.  A continuación, se presenta un resumen visual de lo abarcado.

    .row.justify-content-center(data-aos="fade-right")
      .col-lg-12.mb-5
        figure
          img(src="@/assets/curso/sintesis.svg", alt="alt")
      .col-auto
        a.anexo.mb-4(:href="obtenerLink('/downloads/sintesis.pdf')" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-pdf.svg")
          .anexo__texto
            p Anexo. Síntesis

</template>

<script>
export default {
  name: 'Sintesis',
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
