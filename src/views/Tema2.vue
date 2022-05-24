<template lang="pug">
.curso-main-container.pb-3.tema2
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Informática forense

    p.mb-4(data-aos="fade-right") La informática forense es una rama de la ciencia de la computación que se especializa en el análisis y toma de evidencia en los escenarios donde se cometen delitos informáticos. En muchos aspectos, se puede comparar la informática forense con las labores que se ven dentro de las películas, donde se examinan escenarios y se perfilan personas, se toma evidencia en equipos, etc. Todo esto puede sonar un poco a ciencia ficción, pero muchos de esos procesos son reales y hacen parte de esta disciplina.

    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5(data-aos="fade-left")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema2/img01.svg')})`}"
      )
      .bloque-texto-g__texto.p-4.py-5          
          p.mb-0 <br>Hoy la informática forense ha tomado un nivel de aceptación en el que es uno de los procesos llevados a cabo en miles de organizaciones a lo largo del mundo, ya que permite establecer las causas, motivos y condenar los diferentes actos vandálicos que se cometen contra la infraestructura tecnológica de una organización.<br><br>

    .fondo2

      p.mb-5 Dentro de la informática forense, se encuentran diferentes actividades y procesos que se realizan, los cuales tienen como objetivo principal esclarecer las causas de un delito informático y armar una hipótesis de cómo ocurrieron los hechos. 
    
      .row.justify-content-center.align-items-center.mb-5(data-aos="fade-left")
        .col-12.col-lg-10
          .cajon.color-primario.p-4
            p.mb-0 En la actualidad, la Policía Nacional es el organismo encargado de realizar estas labores mediante los peritos informáticos, los cuales se encargan de recolectar y realizar las actividades forenses a nivel nacional.

      p.mb-5 En el caso de Colombia, país regido por leyes, tanto a nivel penal como administrativas, los delitos informáticos están estipulados en la Ley 1273 de 2009, llamada también Ley de delitos informáticos, en la cual se modifica el Código Penal para sancionarlos. Se instauran diferentes tipos de cláusulas, multas y hasta sanciones de tipo carcelario, dependiendo del tipo de delito cometido, expresadas en los diferentes artículos de esta Ley. A continuación  se mencionan algunos de ellos, los cuales están distribuidos en dos capítulos.

      .tarjeta--container.row.mb-5(data-aos="fade-right")
        //- .tarjeta debe ir acompañado de una de una de estas clases => 
        //- .color-primario, .color-secundario, .color-acento-contenido, .color-acento-botones
        //- estas clases tambien tienen un modificador --borde
        .col-md.tarjeta.color-secundario.p-5.px-lg-5.px-3.mb-4.mb-lg-0
          .row.justify-content-center.mb-4
            .col-9.py-4
              figure
                img(src='@/assets/curso/tema2/img02.svg')
            
          div.px-0.px-lg-5
            h1.text-center(style="font-size:32px") Capítulo primero
            p.mb-4 De los atentados contra la confidencialidad, la integridad y la disponibilidad de los datos y de los sistemas informáticos.
            p.mb-0 <b>Artículo 269A:</b> ACCESO ABUSIVO A UN SISTEMA INFORMÁTICO. El que, sin autorización o por fuera de lo acordado, acceda en todo o en parte a un sistema informático protegido o no con una medida de seguridad, o se mantenga dentro del mismo en contra de la voluntad de quien tenga el legítimo derecho a excluirlo, incurrirá en pena de prisión de cuarenta y ocho (48) a noventa y seis (96) meses y en multa de 100 a 1000 salarios mínimos legales mensuales vigentes.


        //- .tarjeta debe ir acompañado de una de una de estas clases => 
        //- .color-primario, .color-secundario, .color-acento-contenido, .color-acento-botones
        //- estas clases tambien tienen un modificador --borde
        .col-md.tarjeta.color-acento-contenido.p-5.px-lg-5.px-3.mb-4.mb-lg-0(style="background-color: #301850")
          .row.justify-content-center.mb-4
            .col-9.py-4
              figure
                img(src='@/assets/curso/tema2/img03.svg')
            
          div.px-0.px-lg-5
            h1.text-center(style="font-size:32px") Capítulo segundo
            p.mb-4 De las atentados informáticos y otras infracciones.
            p.mb-0 <b>Artículo 269I:</b> HURTO POR MEDIOS INFORMÁTICOS Y SEMEJANTES. El que, superando medidas de seguridad informáticas, realice la conducta señalada en el artículo 239, manipulando un sistema informático, una red de sistema electrónico, telemático u otro medio semejante, o suplantando a un usuario ante los sistemas de autenticación y de autorización establecidos, incurrirá en las penas señaladas en el artículo 240 de este Código.

      .row.justify-content-center.align-items-center.mb-5(data-aos="fade-left")
        .col-12.col-lg-10
          .cajon.color-primario.p-4
            p.mb-0 Gracias a estos mecanismos impuestos en la ley penal, se ha logrado establecer el principio fundamental para el acceso de la información y de los datos. Las empresas de cualquier tipo de proceso administran y manejan determinada información, ya sea desde un hospital hasta la misma Registraduría. La implementación de esta ley permite regular el uso de la información de los usuarios y personas, las cuales son dueñas y propietarias de la misma. En otras palabras, quiere decir que todas las empresas que utilicen información de terceros deben velar por resguardar la información de manera tal que no infrinjan ninguno de los artículos antes expuestos.
    
      .row.justify-content-center.align-items-center.mb-5(data-aos="fade-right")
        .col-12.col-lg-6
          .row.justify-content-center.align-items-center.p-4(style="background-color: #FDE4F6")
            .col-6.col-lg-3
              img.mb-4.mb-lg-0(src='@/assets/curso/tema2/img04.svg')
            .col-12.col-lg-9
              h4 LEY 1273 de enero de 2009
              p.mb-0 Se sugiere explorar los demás artículos contemplados en esta Ley, recurso que se encuentra en el material complementario.

      
    .fondo1
      .row.justify-content-center.align-items-center.mb-5(data-aos="fade-left")
        .col-12.col-lg-5
          p.mb-4 Ahora bien, en el caso de la informática forense, se pueden encontrar diversos factores fundamentales que permiten realizar un seguimiento a los procesos en delitos informáticos.
          p.mb-4.mb-lg-0 Cabe decir que el proceso de la informática forense incluye un conjunto de actividades que se deben realizar y protocolos que también se deben llevar a cabo para efectuar este proceso; no obstante, aunque los procesos por delitos de la seguridad de la información en algunos casos quedan impunes, se resalta el hecho de que los procesos que se llevan a cabo para poder esclarecer los sucesos son rigurosos y muy aplicables, tal como se presenta en el siguiente gráfico interactivo.
        .col-8.col-lg-5
          img(src='@/assets/curso/tema2/img06.png')

      h4.mb-5.text-center Proceso Forense 

      .row.justify-content-center.align-items-center
        .col-12.col-lg-8
          ImagenInfografica.color-acento-botones.mb-5
            template(v-slot:imagen)
              figure
                img(src='@/assets/curso/tema2/img06.svg')                

            .tarjeta.color-acento-botones.p-3(x="1.3%" y="78%" numero="+")
              p.mb-4 <b>Análisis de antecedentes:</b> se procede a la revisión de sucesos que se presentaron en otras ocasiones y que cumplen con la característica de ser similares tanto en el actuar como en los resultados después de cometido el acto. 
              p.mb-0 Cabe aclarar que este aspecto entrega una información muy valiosa para empezar a crear una lista de sospechosos de acuerdo con ataques o delitos cometidos en otros momentos, de ahí la importancia de crear una base de datos de esta información, para luego tomarla como aspecto inicial de la investigación.
            .tarjeta.color-acento-botones.p-3(x="34.2%" y="34%" numero="+")
              p.mb-0 <b>Entrevista con las víctimas:</b> aquí se realizan entrevistas con las personas involucradas en los hechos presentados. En algunas ocasiones, las víctimas terminan siendo cómplices de los delitos cometidos, y se trata inicialmente de descartar esta posibilidad. Otro de los aspectos a tener en cuenta al momento de realizar este proceso es conectar a posibles actores del suceso con las evidencias, es decir, poder establecer hipótesis que permitan llegar a tener detalles de los sucesos, para luego indagar de manera más profunda sobre los involucrados y llegar a personas que no son visibles directamente dentro de la investigación.
            .tarjeta.color-acento-botones.p-3.tarjeta-amplia(x="51.4%" y="97%" numero="+")
              p.mb-4 <b>Levantamiento y toma de evidencia:</b> en este proceso, existe una rigurosidad bastante específica, puesto que la toma de evidencia es uno de los factores determinantes para realizar los procesos que pueden llevar a la solución del delito. Aquí  se determinan inicialmente las herramientas que se deben utilizar para la toma de dichas evidencias, lo cual es tenido en cuenta con los peritos informáticos. 
              p.mb-0 Adicional a ello, el almacenamiento y procesamiento de esas evidencias deben tener unos protocolos y procedimientos bastante complejos, puesto que no se puede permitir que sean alterados datos o información, ya que perderían su validez; en el caso específico de equipos de cómputo que fueron utilizados para cometer el delito, se procede a acordonar el área para que nadie pueda alterar o sustraer información que puede ser fundamental para esclarecer o dar solución al delito cometido. En el material complementario, se encuentra un video para ampliar este aspecto. 
            .tarjeta.color-acento-botones.p-3( x="50.5%" y="4%" numero="+")
              p.mb-4 <b>Entrega de resultado de evidencias:</b> en este punto, se lleva a cabo la entrega de las diferentes evidencias recolectadas y procesadas y que se convierten en el soporte legal. También permiten realizar un veredicto y resolver la situación legal de lo ocurrido. Es importante tener en cuenta que esta evidencia debe pasar por un riguroso proceso de verificación antes de ser entregada e incluida en el caso, para que no genere inconsistencias o entorpezca el debido seguimiento del mismo.
            .tarjeta.color-acento-botones.p-3(x="98.8%" y="27.3%" numero="+")
              p.mb-4 <b>Dictamen y/o veredicto:</b> En esta parte, se encuentra ya el veredicto final, el cual es aplicado por un juez con las competencias para establecer culpabilidad o inocencia de los involucrados en el proceso, de acuerdo con la evidencia presentada y los sucesos.
         
</template>

<script>
export default {
  name: 'Tema2',
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

<style lang="sass">
.tema2


  .tarjeta-amplia
    @media (min-width: 992px)
      width: 450px !important







  .img-infografica.color-acento-botones .img-infografica__item__numero
    color: white
    font-size: 26px

  .tarjeta.color-acento-botones
    background-color: #FFFFFF

  .fondo1
    position: relative
    padding-bottom: 1rem
    h4, img, p
      position: relative
      //z-index: 10000
    &::before
      content: ""
      position: absolute
      top: 0
      left: 2.5%
      width: 134%
      height: 100%
      margin: 0 -5rem
      background-image: url("../assets/curso/tema2/img05.png")
      // background-size: contain
      background-repeat: no-repeat

  .fondo2
    position: relative
    padding-bottom: 1rem
    z-index: 0
    p, img, .tarjeta--container
      position: relative
      z-index: 1

    &::before
      content: ""
      position: absolute
      top: 0
      left: 2.5%
      width: 134%
      height: 100%
      margin: 0 -5rem
      background-image: url("../assets/curso/tema2/img07.svg")
      // background-size: contain
      background-repeat: no-repeat
</style>
