<template lang="pug">
section
  .banner-principal.mb-5
    .container.tarjeta.p-4.p-sm-5(
      :style="{'background-image': `url(${require('@/assets/curso/fondo-banner-principal.png')})`}"
    )
      .row.justify-content-around.align-items-center
        .col-lg-7.col-xxl-6.banner-principal__info
          .banner-principal__programa
            .h1.mb-0 Desarrollo de colecciones para la industria de la moda
          
          .h2 Información del programa
          .banner-principal__datos
            ul
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Nombre del programa: 
                p.banner-principal__datos__item__texto Desarrollo de colecciones para la industria de la moda
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Código: 
                p.banner-principal__datos__item__texto 524300
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Total Horas: 
                p.banner-principal__datos__item__texto 48 Horas
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Duración en meses: 
                p.banner-principal__datos__item__texto 27 meses
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Modalidad: 
                p.banner-principal__datos__item__texto virtual
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Descripción del programa : 
                .banner-principal__datos__item__texto
                  p Estimado aprendiz, bienvenido al programa de formación “Tecnología en Desarrollo de colecciones para la industria de la moda”. A través del siguiente video podrá conocer todos los procesos que se llevarán a cabo para ser un destacado tecnólogo en esta área

        .d-none.d-lg-block.col-lg-5
          //- img(src="@/assets/curso/banner-princiapal.svg")
          .video
            | <iframe data-v-1f9e4816="" width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="allowfullscreen"></iframe>

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 1. Presentación

    p Bienvenido al programa Tecnólogo en Desarrollo de Colecciones para la Industria de la Moda, a través de esta formación usted estará en capacidad de interpretar y materializar diseños creativos definidos por los equipos de diseño de una organización.

    p Así mismo, puede desempeñarse como prestador de servicios de patronaje y desarrollo de prototipos para colecciones de vestuario, destacándose por el conocimiento técnico y el uso de herramientas digitales especializadas en la fabricación de prendas de vestir.  


    p Por medio de esta tecnología, tendrá la oportunidad de conocer el proceso industrial de la confección, adquiriendo habilidades que involucran todos los procesos creativos partiendo del diseño, el trazo, el corte, finalizando en la confección de prendas de vestir con los estándares de calidad exigidos por el mercado actual. 

    p En esta aventura de aprendizaje, el conocimiento técnico y el uso de herramientas digitales proporcionan un valor agregado y diferenciador en el competido mundo de la moda y el vestuario. 


    p Lo invitamos a desarrollar cada uno de los contenidos temáticos en fundamentos de diseño, mercadeo, desarrollo técnico, materiales e insumos, producción e interpretación del diseño para el desarrollo de colecciones para la industria de la moda.  

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 2. Justificación<br>del programa

    p La industria de la confección en el marco de la globalización tiene el reto de ser competitiva en mercados nacionales e internacionales que plantean mayores exigencias y desafíos al mundo empresarial, con la incorporación de innovación tecnológica en el sistema moda. Otro reto, es el cambio constante en los mercados de consumo generado por la variabilidad económica, debido a la entrada de productos importados legales e ilegales, esta realidad requiere que las empresas del sector sean dinámicas en las condiciones productivas, tecnológicas y de mercados existentes y emergentes. 
    p En Colombia el sub sector productivo - diseño confección y moda-, cuenta con empresas que atienden el mercado nacional y se proyectan a las oportunidades del mercado internacional, esto significa una ventaja, en la medida en que las compañías cuenten con una curva de aprendizaje ascendente y de capital humano competente, para afrontar los cambios de ciclos de vida y posicionamiento de producto y marca, en los que se evidencie una visión articulada, entre las estrategias aplicadas a procesos de diseño, desarrollo de colecciones y la cadena suministro, proveedor , productor y consumidor. Con el objetivo de brindar una respuesta pertinente a la industria de la moda, las instituciones de orden superior orientan sus procesos formativos profesionales hacia la gestión de diseño, donde un profesional en diseño de modas y/o diseño de vestuario considera aspectos conceptuales en gestión de la comunicación, gestión de organización y administración, basados en la producción de conocimiento y en la cultura universal con prospectiva para el sistema moda. 
    p El SENA, como entidad de formación para el trabajo a nivel técnico y tecnológico, ofrece el programa Tecnología en Desarrollo de Colecciones para la Industria de la Moda, con énfasis en la interpretación del diseño y el desarrollo de productos acorde con los requerimientos de la industria. El programa identifica el rol del egresado como operativo tecnológico, en términos de apoyar los procesos productivos a partir de la capacidad de interpretación y materialización de las propuestas de diseño, respondiendo a los requerimientos del jefe de área, procesos productivos, las necesidades empresariales y del mercado. 


  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 3. Competencias a desarrollar

    p #[b Técnicas:]
      ul.lista-ul.mt-3  
        li 
          i.lista-ul__vineta
          | 290601216. Diseñar prendas de vestir según técnicas de diseño y normativa.
        li 
          i.lista-ul__vineta
          | 290601217. Desarrollar patrones de acuerdo con procedimientos técnicos.

    p #[b Claves:]
      ul.lista-ul.mt-3
        li 
          i.lista-ul__vineta
          | 240202501. Interactuar en lengua inglesa de forma oral y escrita dentro de contextos sociales y laborales según los criterios establecidos por el Marco Común Europeo de Referencia para las Lenguas.
        li 
          i.lista-ul__vineta
          | 220501046. Utilizar herramientas informáticas de acuerdo con  necesidades de manejo de información.
        li 
          i.lista-ul__vineta
          | 240201528. Razonar cuantitativamente frente a situaciones susceptibles de ser abordadas de manera matemática en contextos laborales, sociales y personales.
        li 
          i.lista-ul__vineta
          | 240201524. Desarrollar procesos de comunicación eficaces y efectivos, teniendo en cuenta situaciones de orden social, personal y productivo.

    p #[b Transversales:]
      ul.lista-ul.mt-3
        li 
          i.lista-ul__vineta
          | 240201064. Orientar investigación formativa según referentes técnicos.
        li 
          i.lista-ul__vineta
          | 240201526. Interactuar en el contexto productivo y social de acuerdo con principios éticos para la construcción de una cultura de paz.
        li 
          i.lista-ul__vineta
          | 220601501. Aplicar prácticas de protección ambiental, seguridad y salud en el trabajo de acuerdo con las políticas organizacionales y la normatividad vigente.
        li 
          i.lista-ul__vineta
          | 230101507. Actividad física. Generar hábitos saludables de vida mediante la aplicación de programas de actividad física en los contextos productivos y sociales.
        li 
          i.lista-ul__vineta
          | 210201501. Ejercer los derechos fundamentales del trabajo de acuerdo al reconocimiento de la dignidad.
        li 
          i.lista-ul__vineta
          | 240201529. Gestionar procesos propios de la cultura emprendedora y empresarial de acuerdo con el perfil personal y los requerimientos de los contextos productivo y social.


  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 4. Perfil de ingreso

    ul.lista-ul.mt-3
      li 
        i.lista-ul__vineta
        | Nivel académico: bachiller.
      li 
        i.lista-ul__vineta
        | Curso  formación para el trabajo y el desarrollo humano: No.
      li 
        i.lista-ul__vineta
        | Número de horas: 
      li 
        i.lista-ul__vineta
        | Requiere certificación académica: Si.
      li 
        i.lista-ul__vineta
        | Requiere experiencia laboral: No.
      li 
        i.lista-ul__vineta
        | Edad mínima definida en la ley: 16 años.
      li 
        i.lista-ul__vineta
        | Requisitos adicionales: presentar certificado prueba de estado de la educación media Saber 11.
      li 
        i.lista-ul__vineta
        | Aspectos actitudinales, motivacionales y de interés: el aspirante debe ser una persona recursiva, propositiva, disciplinada, exploradora, arriesgada, solucionadora de problemas usando sus habilidades y conocimientos. Respetuosa y con buena actitud en el trabajo en equipo. Motivada y curiosa en temas de investigación en desarrollo de producto, innovación, moda, tecnología, referentes influyentes, opinión de líderes, tendencias, arte, sociedad y contexto.

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 5. Perfil de egreso

    p Desarrollo de prendas de vestir según los requerimientos de función, producción y comunicación del producto acordes con las tendencias técnicas / tecnológicas de la empresa y del mercado.

    p #[b Campo ocupacional]: Diseñadores de Teatro, Moda, Exhibición y Otros Diseñadores Creativos.
    p Los productos principales que un tecnólogo en desarrollo de colecciones para la industria de la  moda obtendrá para su trabajo son:
    ul.lista-ul.mt-3
      li 
        i.lista-ul__vineta
        | Brief con requerimientos técnicos, funcionales y de mercado para la producción de prendas de vestir.
      li 
        i.lista-ul__vineta
        | Desarrollo de colecciones de prendas de vestir bajo las condiciones técnico-productivas de la empresa.
      li 
        i.lista-ul__vineta
        | Documentación técnica de prendas de vestir según requerimientos de la empresa.

    p #[b Productos secundarios:]
      ul.lista-ul.mt-3
        li 
          i.lista-ul__vineta
          | Patrones manuales y/o sistematizados.
    p #[b Productos complementarios:]
      ul.lista-ul.mt-3
        li 
          i.lista-ul__vineta
          | Muestra física de producto para prendas de vestir.


  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 6.	Estrategia metodológica

    p Centrada en la construcción de autonomía para garantizar la calidad de la formación en el marco de la formación por competencias, el aprendizaje por proyectos y el uso de técnicas didácticas activas que estimulan el pensamiento para la resolución de problemas simulados y reales; soportadas en el utilización de las tecnologías de la información y la comunicación, integradas, en ambientes virtuales de aprendizaje, que en todo caso recrean el contexto productivo y vinculan al aprendiz con la realidad cotidiana y el desarrollo de las competencias. 

    p Igualmente, debe estimular de manera permanente la autocrítica y la reflexión del aprendiz sobre el que hacer y los resultados de aprendizaje que logra a través de la vinculación activa de las cuatro fuentes de información para la construcción de conocimiento:
    ul.lista-ul.mt-3
      li 
        i.lista-ul__vineta
        | El instructor - Tutor
      li 
        i.lista-ul__vineta
        | El entorno
      li 
        i.lista-ul__vineta
        | las TIC
      li 
        i.lista-ul__vineta
        | El trabajo colaborativo

  //- Créditos
  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 Créditos

    
    .creditos
      div(
        v-for="(creditoKey, index) of Object.keys(creditosData)"
        :class="index != Object.keys(creditosData).length -1 ? 'mb-4' : ''" 
      )
        .creditos__titulo {{configTitulos[creditoKey]}}
        table
          tbody
            tr(
              v-for="(item, idx) of creditosData[creditoKey]" 
              :key="creditoKey+idx"
            )
              td.text-bold(colspan='2' v-html="renderText(item.nombre)")
              td(colspan='2' v-html="renderText(item.cargo)")
              td(colspan='3' v-html="renderText(item.centro)")

  Footer

</template>
<script>
export default {
  name: 'Inicio',
  data: () => ({
    configTitulos: {
      liderEquipo: 'ECOSISTEMA DE RECURSOS EDUCATIVOS DIGITALES',
      contenidoInstruccional: 'CONTENIDO INSTRUCCIONAL',
      desarrolloProducto:
        'DISEÑO Y DESARROLLO DE RECURSOS EDUCATIVOS DIGITALES',
      gestoresRepositorio: 'GESTORES DE REPOSITORIO',
    },
  }),
  computed: {
    creditosData() {
      return this.$config.creditos
    },
  },
  methods: {
    renderText(textObj) {
      let newText = ''
      if (Array.isArray(textObj)) {
        textObj.forEach((texto, index) => {
          newText += (index ? '<br/>' : '') + texto
        })
      } else {
        newText += textObj
      }
      return newText
    },
  },
}
</script>

<style lang="sass">
.creditos
  td, th
    border-color: $color-sistema-c
</style>
