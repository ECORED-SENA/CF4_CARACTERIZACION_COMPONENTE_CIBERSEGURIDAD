<template lang="pug">
.curso-main-container.introduccion.intro
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción

    p.mb-5(data-aos="fade-left") La seguridad de la información es un aspecto importante dentro de las organizaciones, a tal punto que muchas de ellas destinan millones de dólares en la aplicación y puesta en marcha de procesos que aseguren los tres componentes de riesgo establecidos en la norma ISO 27001: integridad, disponibilidad e integridad de la información, factores determinantes para el manejo de la información dentro de una organización. En el siguiente video, se aprecia de manera genérica cada una de las temáticas a desarrollar alrededor de los dispositivos de control y su aplicación en la informática forense.

    figure(data-aos="fade-right")
      .video            
        iframe(iframe width="1280" height="720" src="https://www.youtube.com/embed/7fgF01UoIvs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)  
</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
