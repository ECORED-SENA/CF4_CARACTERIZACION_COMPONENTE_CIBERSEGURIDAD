<template lang="pug">
.curso-main-container.pb-3.tema3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Análisis de evidencia digital

    p.mb-5(data-aos="fade-right") El procedimiento en la toma de evidencias debe estar dentro de un marco de manejo para evitar dañar o corromper los datos y que luego no puedan ser usados en procesos legales. Las evidencias requieren un proceso de manejo muy riguroso, ya que de esta dependen los procesos que se tomarán y que pueden generar inocencia o culpabilidad en una persona, de acuerdo con los hallazgos que se realicen. 

    .row.justify-content-center.align-items-center.mb-5(data-aos="fade-left")
      .col-12.col-lg-10
          .cajon.color-primario.p-4
            p.mb-4 <b>Evidencia digital</b>
            p.mb-0 Es todo elemento o parte utilizada en un sistema de tratamiento de información que provee acceso a un medio tecnológico o una parte en él,  tales como archivo, fichero, memoria <i>USB</i>, equipo de cómputo, llave de acceso, usuario, contraseña, etc. Una evidencia digital es todo aquello que se almacena o procesa mediante medios digitales o sistemas informáticos.

    p.mb-4(data-aos="fade-right") A continuación, se presentan algunas características específicas que toda evidencia digital contiene.

    .row.justify-content-center.align-items-center.mb-5(data-aos="fade-left")
      .col-12.col-lg-6
        LineaTiempoD.color-primario.mb-4.mb-lg-0 
          div(numero="1" titulo="Puede ser duplicada")   
            p.mb-4 Esto significa que la evidencia se compone de dos momentos: uno es la evidencia original y otro, la réplica o clonación de esa información.
            p.mb-4 En la práctica forense, no se puede trabajar con la evidencia original, sino que se realiza un proceso de clonación o duplicación de la información, para realizar las diferentes técnicas o procedimientos para trabajar con ella. 
            p.mb-0 Este proceso se realiza para no alterar la evidencia original que se encontró al momento de realizar el levantamiento de la misma. En casos particulares, las evidencias y sus procesos se realizan en un escenario lo más parecido al original donde se encontró la evidencia, para que los resultados sean más precisos.         
          div(numero="2" titulo="Herramientas de verificación de autenticidad")
            p.mb-0 En este proceso, se pretende utilizar herramientas de <i>software</i> o <i>hardware</i> que permitan establecer si una evidencia ha sido alterada o modificada, de acuerdo con su versión inicial. Lo anterior con el fin de  descartar la evidencia desde un punto inicial y así solo trabajar o clasificar la evidencia que vale la pena procesar y que puede ser utilizada en el proceso judicial; aunque en algunos casos, se puede utilizar para culpar o señalar a presuntos delincuentes sobre la modificación de archivos o ficheros para esconder u ocultar evidencia, lo cual terminaría siendo un delito contemplado en la Ley 1273 de 2009 y se sancionará por ese delito.
          div(numero="3" titulo="Recuperación de evidencia borrada")
            p.mb-4 Se debe tener en cuenta que un delito puede llevar a este proceso de manera recurrente, ya que un posible delincuente informático lo primero que hará es borrar o eliminar la evidencia para evitar la culpabilidad.
            p.mb-0 En este caso, se procede a utilizar <i>software</i> de recuperación, para extraer los archivos que han sido eliminados o borrados de sistemas de tratamiento de información, y luego convertir estos hallazgos en evidencia para ser usada en la solución del caso.
          div(numero="4" titulo="Almacenamiento de evidencias y tratamientos")
            p.mb-4 En este proceso, después de verificar la autenticidad de la evidencia y corroborar que esta no ha sido alterada, se procede a realizar la preservación de la misma. 
            p.mb-0 Esto se debe realizar de manera cuidadosa y en lugares donde solo tienen acceso las personas expertas o autorizadas para la manipulación de dicha información. En la mayoría de casos, se llegan a utilizar bóvedas y contenedores protegidos hasta por medidas biométricas, para garantizar la integridad y confidencialidad de la evidencia.
      .col-8.col-lg-6
        img(src="@/assets/curso/tema3/img01.png")      
    
    p.mb-5(data-aos="fade-right") Ahora bien, para el caso de la estandarización de las respuestas a incidentes, se establece la generación de una forma, protocolo o procedimiento que se debe realizar para garantizar la respuesta adecuada al usuario o al proceso que se lleva a cabo; es decir, se tiene que seguir un lineamiento de acuerdo con unos objetivos definidos, los cuales se tratan en el siguiente recurso.

    TabsB.color-acento-contenido.mb-5(data-aos="fade-left")
      .row.py-5.justify-content-center(titulo="Definición de roles y responsabilidades" :icono="require('@/assets/curso/tema3/img02.svg')")
        .col-12.col-lg-8.py-3
          h4 Definición de roles y responsabilidades
          p.mb-4.mb-lg-0 Se centra en la organización y definición de las personas responsables de realizar el proceso. Esto es importante en la medida en que cada proceso debe tener un responsable para unificar criterios y realizar seguimiento a cada proceso.
        .col-8.col-lg-3
          img(src="@/assets/curso/tema3/img07.png")      
        .col-lg-1
      .row.py-5.justify-content-center(titulo="Gestionar los eventos presentados" :icono="require('@/assets/curso/tema3/img03.svg')")
        .col-12.col-lg-8.py-3
          h4 Gestionar los eventos presentados
          p.mb-4.mb-lg-0 Este componente realiza el proceso de clasificación y detección de los diferentes eventos o incidentes presentados. Se utiliza una escala de valoración, que puede ir de bajo, medio, hasta alto. De acuerdo con esta valoración, se procede a crear las respuestas a entregar.
        .col-8.col-lg-3
          img(src="@/assets/curso/tema3/img08.png")      
        .col-lg-1
      .row.py-5.justify-content-center(titulo="Minimizar los impactos de los incidentes" :icono="require('@/assets/curso/tema3/img04.svg')")
        .col-12.col-lg-8.py-3
          h4 Minimizar los impactos de los incidentes
          p.mb-4.mb-lg-0 Aquí se debe tener en cuenta una gran realidad y es que muchos incidentes no se pueden eliminar del todo y esto hace parte del panorama de riesgo al cual está expuesto el negocio. Por tanto,  lo que se puede hacer es minimizar el impacto que este pueda generar, y en esa medida crear un proceso de respuesta que vaya acorde con el impacto del mismo.
        .col-8.col-lg-3
          img(src="@/assets/curso/tema3/img09.png")      
        .col-lg-1
      .row.py-5.justify-content-center(titulo="Definición de daños y costos" :icono="require('@/assets/curso/tema3/img05.svg')")
        .col-12.col-lg-8.py-3
          h4 Definición de daños y costos
          p.mb-4 En este punto, es importante tener en cuenta que el daño y el costo están estrechamente relacionados. De acuerdo con el nivel de impacto que tenga el incidente, se debe calcular cuál es el costo que esto podría generarle a la organización, aunque esto se puede definir en el plan de recuperación de desastres.
          p.mb-4.mb-lg-0 Hay que establecer cuál será el mecanismo que se debe utilizar para realizar un estudio de costos de acuerdo con información real y no con información desactualizada; es decir, no solo importa el costo monetario del componente, sino también el tiempo que se tomará volver a recuperar el sistema o ponerlo en marcha. Este tiempo se mide en costo, ya que en ocasiones cuesta trabajo adicional, contratación de mano de obra o la adquisición de nuevos componentes para reemplazar lo que sufrió daño.          
        .col-8.col-lg-3
          img(src="@/assets/curso/tema3/img10.png")      
        .col-lg-1
      .row.py-5.justify-content-center(titulo="Procedimientos para la entrega de reporte de incidentes" :icono="require('@/assets/curso/tema3/img06.svg')")
        .col-12.col-lg-8.py-3
          h4 Procedimientos para la entrega de reporte de incidentes
          p.mb-4 En este componente, se debe realizar un paso a paso, es decir, una especie de manual en el cual se especifique cómo se debe realizar el reporte.  En este proceso, se definen los formatos, información solicitada, tales como nombre de quien presenta el reporte, la información del incidente, fecha de reporte del incidente, nivel de gravedad del incidente, para escalar el proceso de acuerdo con la urgencia, y el tratamiento que se le debe realizar al mismo. 
          p.mb-4.mb-lg-0 En muchas ocasiones, esta información permite realizar un tratamiento al incidente de una manera oportuna y disminuir su impacto, o resolverlo con anticipación.          
        .col-8.col-lg-3
          img(src="@/assets/curso/tema3/img11.png")      
        .col-lg-1

    p.mb-4 El proceso de análisis de una evidencia digital, en el caso de ocurrir un incidente, se puede sintetizar de esta manera.
      
    .fondo1.p-0
      .titulo-sexto.color-secundario
        span <b>Figura 1.</b>  Gestión de incidentes

      .row.justify-content-center.mb-5(data-aos="fade-right")
        .col-12.col-lg-8
          img(src="@/assets/curso/tema3/img13.svg")      

      p.mb-5(data-aos="fade-left") La gestión de incidentes se puede abordar desde los siguientes estándares de proceso:

      .row.justify-content-center.mb-5(data-aos="fade-right")
        .col-12.col-lg-5.d-flex
          .tarjeta--boton.color-primario.p-5.mb-5
            .row.justify-content-center.mb-3
              .col-7
                figure
                  img(src='@/assets/curso/tema3/img14.png')

            h3.text-center SOC
            p.mb-0 Son plataformas que permiten la gestión de la seguridad de la información. Sus siglas significan <b>Centros de Operaciones de Seguridad</b>. Estas herramientas permiten la recolección de información y eventos que se pueden presentar, para generar eventos visibles para el personal encargado y así tomar las medidas necesarias de acuerdo con el nivel de riesgo que se pueda presentar. Estos sistemas son indispensables en las organizaciones que deseen mantener un sistema de prevención de riesgo en la infraestructura tecnológica.
        .col-12.col-lg-5.d-flex
          .tarjeta--boton.color-primario.p-5.mb-5
            .row.justify-content-center.mb-3
              .col-7
                figure
                  img(src='@/assets/curso/tema3/img15.png')

            h3.text-center CSIRT
            p.mb-0 Es un equipo de respuesta para el manejo de emergencias de la seguridad de la información, al cual pertenecen un número significativo de profesionales expertos en el tema. Este equipo cuenta con un portafolio de servicios, el cual puede ser usado por las organizaciones interesadas en dichos beneficios. Adicional a esto, cuentan con una base de datos de incidentes presentados y también ofrecen asesoría en este ámbito.

      br
      br
      br
</template>

<script>
export default {
  name: 'Tema3',
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
.linea-tiempo-d.color-primario .linea-tiempo-d__item .linea-tiempo-d__item__number
  span
    font-size: 24px !important

.linea-tiempo-d__item .linea-tiempo-d__item__content__title
  span
    font-size: 20px !important

.tema3
  .fondo1
    position: relative
    padding-bottom: 1rem
    p, div
      position: relative
    &::before
      content: ""
      position: absolute
      top: 0
      left: 2.5%
      width: 134%
      height: 100%
      margin: 0 -5rem
      background-image: url("../assets/curso/tema3/img12.png")
      // background-size: contain
      background-repeat: no-repeat
</style>
