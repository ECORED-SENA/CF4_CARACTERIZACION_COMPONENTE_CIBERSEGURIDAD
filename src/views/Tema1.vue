<template lang="pug">
.curso-main-container.pb-3.tema1
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1 
      h1 Dispositivos de control y monitoreo

    .bloque-texto-g-alrevez.bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5(data-aos="fade-left")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema1/img01.svg')})`}"
      )
      .bloque-texto-g__texto.p-4          
          p.mb-0 La seguridad de la información está tomando una importancia bastante significativa en las organizaciones. Cabe destacar que, hasta no hace muchos años, este aspecto solo era un valor agregado en las organizaciones. Sin embargo, dejó de serlo para convertirse en uno de los pilares de la organización, ya que esta protege uno de los activos más valiosos: la información. De ahí, la necesidad de implementar herramientas y procesos para procurar su protección y buen manejo.
  
    p.mb-5(data-aos="fade-right") Una de las principales tecnologías de protección y fundamental en la implementación para la ciberseguridad es el <i>firewall</i> o también llamado cortafuegos. El video que se presenta a continuación desarrolla en qué consiste su uso.

    figure.mb-5(data-aos="fade-right")
      .video      
        iframe(width="1280" height="720" src="https://www.youtube.com/embed/9orYAFPV1Uc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)  

    p.mb-5(data-aos="fade-left") De igual forma, los IPS, sistemas de protección de intrusos, se encuentran en dos presentaciones: <i>hardware</i> y <i>software</i>. Estos se encargan de realizar un escaneo en la red de información de una organización y son capaces de detectar alguna situación sospechosa y dar alertas sobre la situación que se esté presentando, mediante el envío de correo electrónico o, en algunos casos, mensajes de texto, dependiendo de su configuración. Es importante destacar que los IPS están en la capacidad de bloquear o controlar el tráfico de la red de acuerdo con situaciones detectadas. 

    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5(data-aos="fade-left")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema1/img02.svg')})`}"
      )
      .bloque-texto-g__texto.p-4.py-5          
          p.mb-0 <br>En la actualidad, los IPS utilizan algoritmos de inteligencia artificial para poder predecir una situación de riesgo, o, de acuerdo con unos patrones detectados, bloquear el acceso a ciertos dispositivos o segmentos de la red de datos donde se encuentran los dispositivos críticos o con la información que debe estar protegida.<br><br>

    p.mb-4(data-aos="fade-right") Estos sistemas tienen la capacidad de detectar y guardar en una base de datos la información de cierto usuario y su comportamiento, lo que le permite en próximas ocasiones verificar si se trata del mismo usuario y automáticamente detectarlo y/o bloquearlo. Lo anterior se conoce como <i>Machine Learning</i>, que permite a una máquina utilizar algoritmos de aprendizaje; almacenan información y luego la utilizan para ejecutar funciones específicas.
    p.mb-5(data-aos="fade-left") Los IPS se clasifican de la siguiente manera.

    TabsB.color-acento-contenido.mb-5(data-aos="fade-right")
      .row.py-5.justify-content-center(titulo="IPS basado en firmas" :icono="require('@/assets/curso/tema1/img03.svg')")
        .col-12.col-lg-8.py-3
          h4 IPS basado en firmas
          p.mb-4 Cuenta con una base de datos de firmas ya verificadas y autenticadas para controlar el acceso de los usuarios y permisos a programas o características de acceso. Estas firmas son adicionadas al dispositivo, el cual empieza a ejercer sus funciones. 
          p.mb-4.mb-lg-0  Adicional a esto, tiene un algoritmo de coincidencia, el cual permite verificar los aspectos que tienen un patrón de equivalencia, notificar y realizar las acciones programadas.          
        .col-8.col-lg-3
          img(src="@/assets/curso/tema1/img07.png")      
        .col-lg-1
      .row.py-5.justify-content-center(titulo="IPS basado en firmas" :icono="require('@/assets/curso/tema1/img04.svg')")
        .col-12.col-lg-8.py-3
          h4 IPS basado en anomalías
          p.mb-4.mb-lg-0 Este tipo de IPS realiza un escaneo de perfiles, verifica el comportamiento de los usuarios en el sistema y realiza una verificación sobre las acciones que estos realizan en el sistema; por ejemplo, si un usuario se autentica a una hora específica siempre, o en un rango de hora determinada, y luego cambia esa rutina, el sistema lo detectará como algo sospechoso y realizará las respectivas notificaciones y acciones que se le tengan programadas.
        .col-8.col-lg-3
          img(src="@/assets/curso/tema1/img08.png")      
        .col-lg-1
      .row.py-5.justify-content-center(titulo="IPS basado en firmas" :icono="require('@/assets/curso/tema1/img05.svg')")
        .col-12.col-lg-8.py-3
          h4 IPS basado en políticas
          p.mb-4 Este tipo de IPS requiere, inicialmente, que se le suministren las políticas de una manera específica, para luego entrar en función. 
          p.mb-4.mb-lg-0 Este se encarga de velar por el cumplimiento de rechazar o aceptar y, al mismo tiempo, realizar validaciones sobre acciones realizadas por los usuarios. Tiene un parecido a los <i>firewall</i>, puesto que, por ejemplo, si detecta que un usuario está tratando de enviar un paquete o alguna información fuera de la pactada dentro de las políticas, procede a denegar su acceso y a realizar la notificación correspondiente.          
        .col-8.col-lg-3
          img(src="@/assets/curso/tema1/img09.png")      
        .col-lg-1
      .row.py-5.justify-content-center(titulo="IPS basado en firmas" :icono="require('@/assets/curso/tema1/img06.svg')")
        .col-12.col-lg-8.py-3
          h4 IPS basado en la detección por <i>Honey Pot</i>
          p.mb-4 Se basa en la configuración de un equipo señuelo o carnada, con pocas configuraciones de seguridad y vulnerabilidades, para verificar si un posible atacante intenta acceder o vulnerar, y de esta manera verificar la intención que este tiene con respecto al uso del sistema.
          p.mb-4.mb-lg-0 Este tipo de estrategias son muy utilizadas para medir el grado de intencionalidad que puede tener un posible atacante y también se puede examinar a los usuarios internos de la red y verificar que nadie esté teniendo de manera interna intenciones fuera de las que están estipuladas en los procedimientos de la organización.
        .col-8.col-lg-3
          img(src="@/assets/curso/tema1/img10.png")      
        .col-lg-1

    .fondo1.py-5
      p.mb-4.text-white(data-aos="fade-left") Ahora bien, adicionales a las herramientas anteriormente expuestas, existen otros procesos que permiten monitorear y controlar el manejo que se le da a la seguridad de la información en una organización.      
      .row.justify-content-center(data-aos="fade-right")
        //.col-xl.col-lg-2.col-md-3.col-sm-6.col-6.contenedor-especial(v-on:click="click(1)")
        .col-xl.col-3.contenedor-especial(v-on:click="click(1)")
          img.mb-3(src="@/assets/curso/tema1/img12.svg" ref="img1" v-show="seleccion!=1")      
          img.mb-3(src="@/assets/curso/tema1/img21.svg" ref="img1b" v-show="seleccion==1")      
          h3.text-center.text-white.textoespecial     <i>Antimalware</i>
        .col-xl.col-3.contenedor-especial(v-on:click="click(2)")
          img.mb-3(src="@/assets/curso/tema1/img13.svg" ref="img2" v-show="seleccion!=2")      
          img.mb-3(src="@/assets/curso/tema1/img22.svg" ref="img2b" v-show="seleccion==2")      
          h3.text-center.text-white.textoespecial     <i>Antispam</i>
        .col-xl.col-3.contenedor-especial(v-on:click="click(3)")
          img.mb-3(src="@/assets/curso/tema1/img14.svg" ref="img3" v-show="seleccion!=3")      
          img.mb-3(src="@/assets/curso/tema1/img23.svg" ref="img3b" v-show="seleccion==3")      
          h3.text-center.text-white.textoespecial     <i>Sandboxing</i>
        .col-xl.col-3.contenedor-especial(v-on:click="click(4)")
          img.mb-3(src="@/assets/curso/tema1/img15.svg" ref="img4" v-show="seleccion!=4")      
          img.mb-3(src="@/assets/curso/tema1/img24.svg" ref="img4b" v-show="seleccion==4")      
          h3.text-center.text-white.textoespecial     <i>Firewall</i> de base de datos
        .col-xl.col-3.contenedor-especial(v-on:click="click(5)")
          img.mb-3(src="@/assets/curso/tema1/img16.svg" ref="img5" v-show="seleccion!=5")      
          img.mb-3(src="@/assets/curso/tema1/img25.svg" ref="img5b" v-show="seleccion==5")      
          h3.text-center.text-white.textoespecial     DLP
        .col-xl.col-3.contenedor-especial(v-on:click="click(6)")
          img.mb-3(src="@/assets/curso/tema1/img17.svg" ref="img6" v-show="seleccion!=6")      
          img.mb-3(src="@/assets/curso/tema1/img26.svg" ref="img6b" v-show="seleccion==6")      
          h3.text-center.text-white.textoespecial     NAC
        .col-xl.col-3.contenedor-especial(v-on:click="click(7)")
          img.mb-3(src="@/assets/curso/tema1/img18.svg" ref="img7" v-show="seleccion!=7")      
          img.mb-3(src="@/assets/curso/tema1/img27.svg" ref="img7b" v-show="seleccion==7")      
          h3.text-center.text-white.textoespecial     Parchado virtual
        .col-xl.col-3.contenedor-especial(v-on:click="click(8)")
          img.mb-3(src="@/assets/curso/tema1/img19.svg" ref="img8" v-show="seleccion!=8")              
          img.mb-3(src="@/assets/curso/tema1/img28.svg" ref="img8b" v-show="seleccion==8")      
          h3.text-center.text-white.textoespecial     <i>File Integrity Monitoring</i>

      .row.justify-content-center
        .col-xl.col-3.contenedor-especial.p-0
          img(src="@/assets/curso/tema1/img29.svg" ref="img8" v-show="seleccion==1")              
        .col-xl.col-3.contenedor-especial
          img(src="@/assets/curso/tema1/img29.svg" ref="img8" v-show="seleccion==2")              
        .col-xl.col-3.contenedor-especial
          img(src="@/assets/curso/tema1/img29.svg" ref="img8" v-show="seleccion==3")              
        .col-xl.col-3.contenedor-especial
          img(src="@/assets/curso/tema1/img29.svg" ref="img8" v-show="seleccion==4")              
        .col-xl.col-3.contenedor-especial
          img(src="@/assets/curso/tema1/img29.svg" ref="img8" v-show="seleccion==5")              
        .col-xl.col-3.contenedor-especial
          img(src="@/assets/curso/tema1/img29.svg" ref="img8" v-show="seleccion==6")              
        .col-xl.col-3.contenedor-especial
          img(src="@/assets/curso/tema1/img29.svg" ref="img8" v-show="seleccion==7")              
        .col-xl.col-3.contenedor-especial
          img(src="@/assets/curso/tema1/img29.svg" ref="img8" v-show="seleccion==8")              

      .fondo2.div.p-0(v-if="seleccion!=0" v-bind:data-aos="seleccion!=0?'fade-in':''" )
        div.p-4(style="background-color: #FFFFFF")
          div.p-0(v-show="seleccion==1")
            p.mb-4 Antes de definir qué es un <i>antimalware</i>, se debe realizar un repaso sobre lo que es un <i>malware</i>. El <i>malware</i> es un tipo de virus que realiza modificaciones en el funcionamiento de un sistema, básicamente, es un algoritmo que puede transformarse y realizar procesos para generar vulnerabilidades en un sistema de información. Para casos particulares, el <i>malware</i> tiene variaciones, realizando funciones específicas, donde se encuentran los virus troyanos, gusanos <i>spyware</i>, entre otros.
            p.mb-0 Un <i>antimalware</i>, entonces, es un <i>software</i> que se dedica a monitorear y a contraatacar el <i>malware</i> que se pueda presentar en un equipo. Adicional a esto, tiene la capacidad de generar alertas sobre intrusiones de <i>malware</i> y eliminarlo del equipo.
          div.p-0(v-show="seleccion==2")
            p.mb-4 Es un servicio que suele instalarse en los servidores de correo electrónico y no permite que lleguen correos no deseados o con contenido no confiable. 
            p.mb-4 En la actualidad, casi todos los servicios de mensajería de correo electrónico aplican este tipo de servicios, aunque se puede llegar a pensar que solo rechazan o clasifican correos electrónicos. Esto llega a ser, en algunas ocasiones, más grave de lo que parece, puesto que los mensajes de dudosa procedencia son los que permiten un ataque informático llamado <i>phishing</i>, el cual tiene como objetivo capturar la información y hacerse pasar por otra persona o compañía para robar la información de los usuarios.
            p.mb-0 El <i>antispam</i> es un servicio muy útil en las organizaciones para prevenir este tipo de fraude informático.
          div.p-0(v-show="seleccion==3")
            p.mb-4 Es un proceso que se utiliza en las organizaciones para ejecutar aplicaciones o códigos en forma aislada del sistema original. Es decir, se realiza de manera controlada para que no afecte al sistema principal. 
            p.mb-0 Esta técnica es muy utilizada, sobre todo cuando se tiene un flujo alto de aplicaciones y procesos dentro de las organizaciones.
          div.p-0(v-show="seleccion==4")
            p.mb-0 Es un <i>software</i> que se utiliza para conectar las reglas de negocio y seguridad, de tal manera que sólo permita el acceso a aplicaciones, servicios e información que hace parte del negocio. Este tipo de <i>software</i> integra una base de datos donde se le configuran las políticas que debe ejecutar y permite el acceso o negación a todo aquello que no está incluido dentro de la regla de negocio o política configurada.
          div.p-0(v-show="seleccion==5")
            p.mb-4 Son soluciones que se integran a los sistemas de información y redes de datos para la prevención de la pérdida de datos que se pueda presentar.
            p.mb-0 Esto se realiza tanto en la transmisión de datos como en los sistemas de almacenamiento. Adicionalmente, ofrecen un interesante sistema de recuperación, el cual puede ser utilizado para mejorar los procesos de resguardo de información, entre otros procesos, y puede realizarlo en cualquier espacio de la infraestructura, ya sea local, remoto o en la nube.
          div.p-0(v-show="seleccion==6")
            p.mb-0 Son controles de acceso que se implementan en los equipos finales donde se resguarda y procesa la información, con el propósito de reforzar procesos como la autenticación de usuarios y el acceso a la red de la organización. En otro sentido, es la manera como se unen diferentes tecnologías para un fin común, el cual es la seguridad de la información de la organización.
          div.p-0(v-show="seleccion==7")
            p.mb-4 El proceso de parchado virtual permite la integración de parches de seguridad para los dispositivos e infraestructura de la organización, con la ventaja que no es necesario realizar su instalación. 
            p.mb-4 En el caso más particular, se encuentran los parches de seguridad para <i>Exploit</i>, el cual es un algoritmo que está enfocado en una vulnerabilidad de los sistemas operativos y que, la mayoría de veces, resulta imposible salvarse de dicho tipo de ataque. La única manera de poder no ser víctima de este es realizando el parchado de seguridad de los sistemas operativos y sistemas que interactúan con la seguridad de la información.
            p.mb-0 Este tipo de procesos de parchado virtual ha tomado fuerza en los tiempos actuales, ya que es mucho más sencillo de implementar, mantener actualizados los sistemas y, adicional a ello, garantiza una constante comunicación con los proveedores de seguridad de estos mismos.
          div.p-0(v-show="seleccion==8")
            p.mb-4 Es un proceso que se realiza para el monitoreo y verificación en la integridad de los archivos; esto incluye tanto archivos del sistema operativo como los que son producidos e integrados al sistema de información.
            p.mb-0 Permite verificar que los archivos no sufran modificaciones, las cuales pueden ser producto de manipulación por parte de programas maliciosos o de dudosa procedencia.
        .row.justify-content-center
          .col-10(style="background-color: #F24DC3; height: 8px !important")
            p.mb-0 
</template>

<script>
export default {
  name: 'Tema1',
  data: () => ({
    seleccion: 0,
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
  methods: {
    click: function(val) {
      this.seleccion = val
    },
  },
}
</script>

<style lang="sass">
.tema1
  .textoespecial
    overflow-wrap: break-word;

  .contenedor-especial
    cursor: pointer

  .fondo2


  .fondo1
    position: relative
    padding-bottom: 1rem
    p, img, h3, .fondo2
      position: relative
    &::before
      content: ""
      position: absolute
      top: 0
      left: 2.5%
      width: 134%
      height: 100%
      margin: 0 -5rem
      //background-color: #015EA4
      background-image: url("../assets/curso/tema1/img11.png")
      background-size: cover
      background-repeat: no-repeat

  .bloque-texto-g-alrevez.bloque-texto-g
      justify-content: flex-start;

  .bloque-texto-g-alrevez
    .bloque-texto-g__img
      right: 0 !important
      left: inherit !important
</style>
