<template lang="pug">
.curso-main-container.pb-3.tema1
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Participación social
      
    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema1/1.png')})`}"
      )
      .bloque-texto-g__texto.p-5
        p.mb-0 La participación ciudadana es aquella que facilita la intervención de toda persona, de manera individual o colectiva, en todos los asuntos de gestión pública, logrando así el control social (enfocado en el seguimiento y la evaluación de las políticas públicas), las acciones de diálogo, los mecanismos de acceso a la información y todos los elementos de mejora continua. Asimismo, la participación comunitaria es aquella que proviene de las acciones de tipo colectivo, donde un grupo de personas que comparten una necesidad, problema o interés trabajan en equipo para conocer las causas y así proponer soluciones y toma de decisiones. 

    p(data-aos="fade-right") En ambas actividades, tanto en la participación ciudadana como comunitaria, se deben generar acciones de veeduría como método de vigilancia sobre las acciones de gestión pública en salud. En el marco de la participación ciudadana, existen servicios de apoyo a la ejecución de sus acciones de vigilancia y control, las denominadas: servicio de atención al usuario, servicio de atención a la comunidad y sistema de atención e información a usuarios. Respecto a la participación comunitaria, se cuenta con los comités de participación comunitaria en salud, los denominados COPACOS. 
    p(data-aos="fade-left").mb-5 En relación con la normativa que regula la participación social, se tienen las siguientes leyes:

    .row.justify-content-center.align-items-center.mb-5
      .col-10
        ol.lista-ol--cuadro.mb-5
          li 
            .lista-ol--cuadro__vineta
              span(style="color:#000 !important") <strong>1</strong>
            | Las acciones de veeduría se encuentran reguladas y tienen sus bases en la #[b Ley 850 de 2003], la cual fue modificada por la #[b Ley 1757 de 2015]. Los objetivos propuestos en esta ley se indican en el siguiente gráfico:

        .row.justify-content-center.align-items-center.mb-5
          .col-10.col-md-10.col-lg-10.desktop(data-aos="fade-right")
            .titulo-sexto.color-acento-contenido
              p.titulo.pb-0.mb-0 #[b Figura 1.] <em>Objetivos de la Ley 1757 de 2015</em>
            figure
              img.mb-3(src='@/assets/curso/temas/tema1/2.svg', alt='La figura 1, indica los objetivos trazados en la ley 1757 de 2015, por la cual se dictan disposiciones en materia de promoción y protección del derecho a la participación democrática.')

        .row.justify-content-center.align-items-center.mb-5
          .col-10.col-md-10.col-lg-10.movil(data-aos="fade-right")
            .titulo-sexto.color-acento-contenido
              p.titulo.pb-0.mb-0 #[b Figura 1.] <em>Objetivos de la Ley 1757 de 2015</em>
            figure
              img.mb-3(src='@/assets/curso/temas/tema1/2-m.svg', alt='La figura 1, indica los objetivos trazados en la ley 1757 de 2015, por la cual se dictan disposiciones en materia de promoción y protección del derecho a la participación democrática.')

        p(data-aos="fade-left").mb-5 Además de los objetivos indicados en la Ley 1757, se proyectan principios relacionados con las acciones de veeduría, estos son:

        .row(data-aos="fade-left").mb-5
          .col-sm-6.col-lg-3.mb-4.mb-lg-0
            .tarjeta--boton.color-secundario.p-4(style='height:100%')
              .row.justify-content-center.mb-3
                .col-7
                  figure
                    img(src='@/assets/curso/temas/tema1/3.svg', alt='Texto que describa la imagen')

              h3.text-center Democratización

          .col-sm-6.col-lg-3.mb-4.mb-lg-0
            .tarjeta--boton.color-primario.p-4(style='height:100%')
              .row.justify-content-center.mb-3
                .col-7
                  figure
                    img(src='@/assets/curso/temas/tema1/4.svg', alt='Texto que describa la imagen')

              h3.text-center Autonomía

          .col-sm-6.col-lg-3.mb-4.mb-sm-0
            .tarjeta--boton.color-secundario.p-4(style='height:100%')
              .row.justify-content-center.mb-3
                .col-7
                  figure
                    img(src='@/assets/curso/temas/tema1/5.svg', alt='Texto que describa la imagen')

              h3.text-center Transparencia

          .col-sm-6.col-lg-3
            .tarjeta--boton.color-primario.p-4(style='height:100%')
              .row.justify-content-center.mb-3
                .col-7
                  figure
                    img(src='@/assets/curso/temas/tema1/6.svg', alt='Texto que describa la imagen')

              h3.text-center Igualdad

        .row(data-aos="fade-left").mb-5
          .col-sm-6.col-lg-3.mb-4.mb-lg-0
            .tarjeta--boton.color-primario.p-4(style='height:100%')
              .row.justify-content-center.mb-3
                .col-7
                  figure
                    img(src='@/assets/curso/temas/tema1/7.svg', alt='Texto que describa la imagen')

              h3.text-center Responsabilidad

          .col-sm-6.col-lg-3.mb-4.mb-lg-0
            .tarjeta--boton.color-secundario.p-4(style='height:100%')
              .row.justify-content-center.mb-3
                .col-7
                  figure
                    img(src='@/assets/curso/temas/tema1/8.svg', alt='Texto que describa la imagen')

              h3.text-center Eficacia

          .col-sm-6.col-lg-3.mb-4.mb-sm-0
            .tarjeta--boton.color-primario.p-4(style='height:100%')
              .row.justify-content-center.mb-3
                .col-7
                  figure
                    img(src='@/assets/curso/temas/tema1/9.svg', alt='Texto que describa la imagen')

              h3.text-center Objetividad

          .col-sm-6.col-lg-3
            .tarjeta--boton.color-secundario.p-4(style='height:100%')
              .row.justify-content-center.mb-3
                .col-7
                  figure
                    img(src='@/assets/curso/temas/tema1/10.svg', alt='Texto que describa la imagen')

              h3.text-center Legalidad

        ol.lista-ol--cuadro.mb-5
          li 
            .lista-ol--cuadro__vineta
              span(style="color:#000 !important") <strong>2</strong>
            | Comprender el alcance de la política de participación social requiere revisar las bases jurídicas establecidas desde la #[b Ley 1438 de 2011] y de la #[b Ley estatutaria 1751 de 2015.]
        p(data-aos="fade-left").mb-5 De acuerdo con el marco de la Ley 1438 de 2011, la participación social está enmarcada en las siguientes estrategias: 

    .BGIMG01.p-4.mb-5
      SlyderA(tipo="b")
        .row
          .col-md-6.mb-4.mb-md-0
            h3 Atención primaria en salud: la atención primaria en salud APS
            p Está conformada por tres componentes integrados, que son: los servicios de salud, la participación comunitaria y ciudadana.

          .col-md-6
            figure
              img(src='@/assets/curso/temas/tema1/11.png', alt='Texto que describa la imagen')

        .row
          .col-md-6.mb-4.mb-md-0
            h3 Redes integradas de servicios de salud
            p Entre los criterios determinantes para la conformación de estas redes, se hace necesario contar con los esquemas de participación social de manera amplia y organizada.

          .col-md-6
            figure
              img(src='@/assets/curso/temas/tema1/12.png', alt='Texto que describa la imagen')

        .row
          .col-md-6.mb-4.mb-md-0
            h3 Plan decenal de dalud pública
            p Para la elaboración del plan, es necesario contar con un proceso amplio de participación social, el cual debe ser eficaz y fortalecerse por medio de la promoción de la capacitación de la ciudadanía y de las organizaciones sociales.

          .col-md-6
            figure
              img(src='@/assets/curso/temas/tema1/13.png', alt='Texto que describa la imagen')

        .row
          .col-md-6.mb-4.mb-md-0
            h3 Política nacional de participación social
            p Esta política requiere contar con varios objetivos:
            ul.lista-ul
              li 
                i.lista-ul__vineta
                | Fortalecer la intervención ciudadana en el diseño de políticas públicas en salud. 
              li 
                i.lista-ul__vineta
                | Fortalecer la cultura de salud y acciones de autocuidado, cambiando factores de riesgo y estimulando protectores de salud. 
              li 
                i.lista-ul__vineta
                | Estimular la veeduría de recursos de salud, cumplimiento de planes de beneficios, actividades y estrategias. 
              li 
                i.lista-ul__vineta
                | Cooperar en la estructuración de políticas y presupuestos en salud.

          .col-md-6
            figure
              img(src='@/assets/curso/temas/tema1/14.png', alt='Texto que describa la imagen')
     
    p(data-aos="fade-left").mb-5 Adicional a lo anterior, tanto la #[b Ley 1751] como la #[b 1757], ambas del año #[b 2015], complementaron los lineamientos a tener en cuenta dentro de la política de participación ciudadana de la siguiente manera: 

    .tarjeta--container.row.mb-5
      .col-md.tarjeta.color-primario.p-5
        .row.justify-content-center.mb-4
          .col-6
            figure
              img(src='@/assets/curso/temas/tema1/15.svg', alt='Texto que describa la imagen')
          
        h2.text-center Ley 1751 de 2015
        p #[b Objeto:] Regular el derecho fundamental a la salud. 
        p #[b Artículo 6:] enuncia un derecho fundamental, la aceptabilidad: refiere al respeto de los actores del sistema sobre aspectos de la ética médica de las diversas culturas de las personas, minorías étnicas, pueblos y comunidades, de las particularidades socioculturales y cosmovisión de la salud, permitiendo la participación de todos en las decisiones del sistema de salud que le afecten. 
        p #[b Artículo 12:] refiere a la participación de todos en las decisiones del sistema de salud como un derecho fundamental.

      .col-md.tarjeta.color-secundario.p-5
        .row.justify-content-center.mb-4
          .col-6
            figure
              img(src='@/assets/curso/temas/tema1/16.svg', alt='Texto que describa la imagen')
          
        h2.text-center Ley 1757 de 2015
        p #[b Objeto:] Dictar las disposiciones en materia de promoción y protección del derecho a la participación democrática. 
        p  Esta ley reglamenta las acciones de iniciativa popular y se dictan las normas y disposiciones ante las corporaciones públicas, el referendo, la consulta popular, la revocatoria del mandato, el plebiscito y el cabildo abierto; de igual manera, se establecen las normas fundamentales por las que se rige la participación democrática de las organizaciones de tipo civil.

    .cajon.color-secundario.p-5.mb-5
      p Son derechos de la Ley 1751 de 2015: 
      ol.lista-ol
        li 
          span.text-bold a. 
          | Intervenir en la formulación de la política de salud, al igual que en los planes para su debida implementación. 
        li 
          span.text-bold b. 
          | Colaborar en las diversas instancias de deliberación, veeduría y seguimiento del sistema. 
        li 
          span.text-bold c. 
          | Contribuir en los programas de promoción y prevención para que sean establecidos. 
        li 
          span.text-bold d. 
          | Cooperar en las decisiones de inclusión o exclusión de los servicios y tecnologías. 
        li 
          span.text-bold e. 
          | Intervenir en los procesos de definición de las prioridades de salud. 
        li 
          span.text-bold f. 
          | Cooperar en todas las decisiones que puedan representar una limitación o restricción en las condiciones de acceso a las instituciones de salud. 
        li 
          span.text-bold g. 
          | Contribuir en la evaluación de los resultados de las políticas de salud.

    .row.justify-content-center.mb-4
      .col-10
        ol.lista-ol--cuadro.mb-5
          li 
            .lista-ol--cuadro__vineta
              span(style="color:#000 !important") <strong>3</strong>
            | En cuanto a la Gestión de la Salud Pública, existen algunas directrices en torno a la ejecución, seguimiento y evaluación del Plan de Salud Pública de Intervenciones Colectivas (PIC); este lineamiento se generó por medio de la #[b Resolución 518 de 2015]. En esta resolución, está claro que, para alcanzar los resultados esperados en esta gestión, se deben implementar y fortalecer los mecanismos de participación social. 

        p Esta resolución (518 de 2015) cuenta con un amplio listado que sirven para contribuir al Plan de Intervenciones Colectivas (PIC); estás intervenciones están orientadas hacia: 

    .BGIMG01.p-4.mb-5
      SlyderA(tipo="b")
        .row
          .col-md-6.mb-4.mb-md-0
            h3 Rehabilitación Basada en Comunidad – RBC
            p Estrategia de nivel intersectorial que busca la inclusión social y desarrollo comunitario, logrando la creación de oportunidades para la población en condición de discapacidad y/o afectaciones psicosociales, familias y cuidadores.

          .col-md-6
            figure
              img(src='@/assets/curso/temas/tema1/17.png', alt='Texto que describa la imagen')

        .row
          .col-md-6.mb-4.mb-md-0
            h3 Prevención y control de vectores
            p Procedimientos que favorecen la planificación, organización, puesta en marcha, control y evaluación de actividades creadas en función de los riesgos ambientales y de comportamiento dirigidos a prevenir, reducir y disminuir la propagación de vectores, así como el contacto entre agentes patógenos y el ser humano.

          .col-md-6
            figure
              img(src='@/assets/curso/temas/tema1/18.png', alt='Texto que describa la imagen')

        .row
          .col-md-6.mb-4.mb-md-0
            h3 Conformación y fortalecimiento de redes sociales, comunitarias, sectoriales e intersectoriales
            p Proceso que se lleva a cabo con: personas, familias, comunidades, organizaciones y redes tanto públicas como privadas, para su propio bien, logrando desarrollar relaciones, interacciones y diversas capacidades que permiten sumar esfuerzos y lazos de cooperación con el objetivo de alcanzar el bien común en el marco de lo requerido.

          .col-md-6
            figure
              img(src='@/assets/curso/temas/tema1/19.png', alt='Texto que describa la imagen')

        .row
          .col-md-6.mb-4.mb-md-0
            h3 Zonas de orientación y centros de escucha
            p Grupos de diversos procedimientos dirigidos a crear espacios de relación constante con las comunidades. Estas acciones están definidas en torno a la escucha activa, acompañamiento, asistencia, acciones de formación y capacitación, referenciación a servicios que se requieran, con el fin de cubrir las demandas y requerimientos de las comunidades.

          .col-md-6
            figure
              img(src='@/assets/curso/temas/tema1/20.png', alt='Texto que describa la imagen')

        .row
          .col-md-6.mb-4.mb-md-0
            h3 Información en salud
            p Entrega de datos e información que ayuden a orientar personas, familias y comunidades en temas relacionados con salud pública, con actores que hacen parte del sistema general de seguridad social en salud; logrando la construcción de elementos colaborativos en la toma de decisiones en torno a la salud.

          .col-md-6
            figure
              img(src='@/assets/curso/temas/tema1/21.png', alt='Texto que describa la imagen')

        .row
          .col-md-6.mb-4.mb-md-0
            h3 Educación y comunicación para la salud
            p Se enfoca en el diálogo de saberes que tiene como fin el desarrollo y el fortalecimiento de las personas, las familias y las comunidades en torno a las acciones de promoción de la salud, la gestión del riesgo y el cambio de los entornos de manera positiva.

          .col-md-6
            figure
              img(src='@/assets/curso/temas/tema1/22.png', alt='Texto que describa la imagen')

        .row
          .col-md-6.mb-4.mb-md-0
            h3 Intervención de la población trabajadora informal
            p Son todas las acciones orientadas a mejorar el bienestar y buscar la protección de la salud para la población que ejecuta actividades laborales de manera informal.

          .col-md-6
            figure
              img(src='@/assets/curso/temas/tema1/23.png', alt='Texto que describa la imagen')

    p(data-aos="fade-left").mb-5 Adicionalmente a las estrategias de intervención, se cuenta con otros elementos que fortalecen el plan de intervenciones colectivas. En la siguiente tabla, pueden identificarse, a manera de ejemplo, las siguientes: 

    .titulo-sexto.color-acento-contenido
      p.titulo.pb-0.mb-0 #[b Tabla 1.] <em>Intervenciones colectivas según Resolución 0518 de 2015</em>
    .tabla-a.color-acento-contenido.mb-5
      table
        caption Nota. Ministerio de Salud y Protección Social.  Resolución 0518 de 2015.
        thead
          tr
            th #[b Procedimientos]
            th(colspan="4") #[p #[b Actividades de canalización:] ayudan a gestionar el acceso efectivo de las personas, las familias y las comunidades a los servicios de salud y de tipo social.]
        tbody
          tr
            td(rowspan="2")(style="background-color:#F1ECE6") #[b Actividades] 
            td(style="background-color:#F6F6F6") #[b Caracterización social y ambiental]
            td(style="background-color:#F6F6F6") #[b Tamizaje]
            td(style="background-color:#F6F6F6") #[b Jornadas de salud]
            td(style="background-color:#F6F6F6") #[b Vacunación antirrábica]
          tr
            td Conocer y describir el entorno social y ambiental de las personas y las comunidades. 
            td Métodos e instrumentos con el fin de conocer diversos eventos en salud. 
              br
              br
              | Para la ejecución de esta actividad, es necesario garantizar el acceso de la persona a la cual se le ha identificado algún evento al servicio integral de atención en salud.  
            td Se refiere al despliegue de un equipo interdisciplinario hacia poblaciones ubicadas principalmente en áreas rurales, con el fin de garantizar el acceso de las poblaciones a los servicios de salud. 
            td Suministro de inmunobiológico a gatos y perros, con el objetivo de generar protección contra la rabia. 
          tr
            td(style="background-color:#F6F6F6") #[b Insumos]
            td(style="background-color:#F6F6F6")(colspan="4") #[b Biológico: es el producto que se utiliza para producir inmunidad (activa-artificial) contra una enfermedad.]
              br
              br
              | #[b Otros: bienes requeridos para el desarrollo e implementación de todos los programas, proyectos y las diversas estrategias en salud pública.]
          tr
            td(style="background-color:#F1ECE6") #[b Medicamentos]
            td(colspan="4") #[b Se utilizan para la prevención, alivio, diagnóstico, tratamiento, curación, rehabilitación de las diversas enfermedades de interés en salud pública.]
              br
              br
              ul.lista-ul
                li 
                  i.lista-ul__vineta
                  | Medicamentos para el control y prevención de la tuberculosis según guías y protocolos definidos por la nación.
                li 
                  i.lista-ul__vineta
                  | Medicamentos para el control de la lepra según guías y protocolos definidos por la nación. 
                li 
                  i.lista-ul__vineta
                  | Medicamentos para el control de la malaria según guías y protocolos definidos por la nación. 
                li 
                  i.lista-ul__vineta
                  | Medicamentos para el control de la Leishmaniasis según guías y protocolos definidos por la nación. 
                li 
                  i.lista-ul__vineta
                  | Medicamentos para el control del Chagas según guías y protocolos definidos por la nación. 
                li 
                  i.lista-ul__vineta
                  | Medicamentos de uso masivo para la prevención, control y eliminación de las   enfermedades infecciosas desatendidas según guías y protocolos definidos por la nación. 

    .row.justify-content-center.align-items-center.mb-5
      .col-10
        .row.mb-5 
          .col-5
            img(src='@/assets/curso/temas/tema1/24.png')
          .col-7 
            ol.lista-ol--cuadro.mb-5
              li 
                .lista-ol--cuadro__vineta
                  span(style="color:#000 !important") <strong>4</strong>
                | Posterior a la divulgación de la Resolución 518 y las leyes mencionadas, es emitida la #[b Resolución 429 del año 2016], la cual tiene como objeto adoptar la Política de Atención Integral en Salud (PAIS). En esta, se establecen los mecanismos de retroalimentación y planes de mejora, los cuales señalan que el modelo integral de atención necesita procesos de retroalimentación dinámicos y constantes en pro de mejorar el desempeño y el resultado en salud; por esta razón, se hace necesario tener cambios en el marco de la participación social, las estrategias de incentivos de financiamiento y métodos de difusión e información. 

        ol.lista-ol--cuadro.mb-5
          li 
            .lista-ol--cuadro__vineta
              span(style="color:#000 !important") <strong>5</strong>
            | Adicionalmente a los lineamientos normativos ya nombrados, se debe resaltar la puesta en marcha de la política de participación social para todas las entidades del sistema de salud; la Resolución 2063 de 2017, la cual nace para hacer cumplir los lineamientos de participación social que fueron ordenados por medio de la Ley 1438 de 2011, la Ley Estatutaria de Salud 1751 de 2015 y la Ley Estatutaria de Participación 1757 de 2015. La política de participación social en salud fue construida por medio de talleres y espacios de deliberación con las comunidades y el sector salud. En la Resolución 2063, se exponen los principios de la política de participación social en salud, los cuales se enfocan en derechos, territorialidad, diversidad, solidaridad, autonomía, equidad, transparencia y corresponsabilidad. Además, se describen los ejes y las líneas de acción de la política de participación social en salud. 
        p En la descripción de los ejes y las líneas de acción, se pueden citar los siguientes: 

    AcordionA(tipo="a" clase-tarjeta="tarjeta color-secundario2")(data-aos="flip-up").mb-5 
      .row(titulo="Eje 1: fortalecimiento a nivel institucional.")
        .col-md-6.mb-4.mb-md-0
          h3 Línea de acción. 
          p Destinación de recursos financieros; proyectar programas de formación y capacitación al personal del sector salud; construir estrategia de asistencia técnica a las entidades territoriales; diseñar los mecanismos de cofinanciación de proyectos de inversión en los diferentes niveles del gobierno; ejecutar las diversas gestiones a nivel interinstitucional para la formación de la comunidad; establecer los lineamientos de las entidades territoriales y demás entidades del sector salud; transversalizar los procesos y dinámicas de participación social en el ciclo de las políticas públicas del sector salud a nivel nacional y territorial; incluir el enfoque diferencial en el desarrollo de los diversos espacios de participación en salud y organizar los respectivos ajustes normativos que permitan la participación en la gestión de los procesos de salud en los diferentes niveles territoriales e institucionales.
      
        .col-md-6
          figure
            img(src='@/assets/curso/temas/tema1/25.png', alt='Texto que describa la imagen')

      .row(titulo="Eje 2: empoderamiento de la ciudadanía y las organizaciones sociales en salud.")
        .col-md-6.mb-4.mb-md-0
          h3 Línea de acción. 
          p Establecer estrategias pedagógicas permanentes en salud para la formación de los ciudadanos; diseñar incentivos que faciliten la participación social y comunitaria; promover el uso de tecnologías de la información y la comunicación, incluyendo el acceso a medios, boletines, periódicos; gestionar las diversas formas de participación; procurar la gestión de recursos para la financiación de las iniciativas comunitarias; organizar los lineamientos que ayuden a las entidades territoriales a presupuestar los recursos requeridos para garantizar la participación de la comunidad; concretar las estrategias de fortalecimiento en el marco de la representación de las comunidades en los espacios de participación de políticas públicas en salud; y organizar los mecanismos de consulta y de la transferencia de la información requerida para garantizar la participación de la comunidad.
      
        .col-md-6
          figure
            img(src='@/assets/curso/temas/tema1/26.png', alt='Texto que describa la imagen')

      .row(titulo="Eje 3: impulso a la cultura de la salud.")
        .col-md-6.mb-4.mb-md-0
          h3 Línea de acción. 
          p Determinar y poner en marcha las diversas estrategias de formación para mejorar la salud pública en alianza con las comunidades; organizar una estrategia de comunicación e información para la promoción y socialización de cultura de bienestar y salud con miras a nivel comunitario; facilitar un programa de formación en el marco de la estrategia formador de formadores comunitarios en salud pública con énfasis en derecho diferencial y de género; organizar y consolidar las estrategias y espacios para que los ciudadanos participen y se apropien de los programas de promoción y prevención; incluir en la política de participación las directrices de salud pública dirigidas a las entidades territoriales; e incorporar la política de participación en los lineamientos de salud pública destinados a las entidades territoriales.
      
        .col-md-6
          figure
            img(src='@/assets/curso/temas/tema1/27.png', alt='Texto que describa la imagen')

      .row(titulo="Eje 4: control social en salud.")
        .col-md-6.mb-4.mb-md-0
          h3 Línea de acción. 
          p Estimular los procesos de enseñanza y formación para incrementar las capacidades ciudadanas en lugares de control social en salud en relación con la gestión pública; facilitar a la ciudadanía el acceso a datos mediante el fortalecimiento de canales de comunicación de las instituciones; tener el control social como eje democrático y de la transparencia, reconociendo a veedores y sus redes; poner en práctica medios que mejoren la participación ciudadana en el análisis de datos, garantizando así la ética en el tema público; concretar y practicar los mecanismos de formación orientados a funcionarios y ciudadanía, con el fin de promocionar la regulación social en las instituciones; y establecer un observatorio de participación y control social en salud.
      
        .col-md-6
          figure
            img(src='@/assets/curso/temas/tema1/28.png', alt='Texto que describa la imagen')
      
      .row(titulo="Eje 5: gestión y garantía en salud con participación en el proceso de decisión.")
        .col-md-6.mb-4.mb-md-0
          h3 Línea de acción. 
          p Construir y poner en marcha los diversos métodos de planificación, con el fin de garantizar la participación de la población en el reconocimiento, priorización, proyección de presupuesto, atenciones en salud y la solución de las problemáticas de salud en el entorno; poner en práctica los métodos que le permitan a los ciudadanos participar en la gestión del sector salud a nivel territorial e institucional; determinar los métodos que permitan la participación de los ciudadanos en torno a los asuntos de inversión pública; y favorecer los espacios para la participación en las decisiones.
      
        .col-md-6
          figure
            img(src='@/assets/curso/temas/tema1/29.png', alt='Texto que describa la imagen')

    p(data-aos="fade-left").mb-5 La política de participación social en salud genera diversas responsabilidades y deberes, los cuales pueden resumirse en el siguiente gráfico:

    .row.justify-content-center.align-items-center.mb-5
      .col-10.col-md-10.col-lg-10.desktop(data-aos="fade-right")
        .titulo-sexto.color-acento-contenido
          p.titulo.pb-0.mb-0 #[b Figura 2.] <em>Deberes y responsabilidades de la política de participación social</em>
        figure
          img.mb-3(src='@/assets/curso/temas/tema1/30.svg', alt='En la figura 2 se establecen las responsabilidades y deberes de la política de participación social.')
          figcaption Nota. Ministerio de Salud y Protección Social.  Resolución 2063 de 2017.

    .row.justify-content-center.align-items-center.mb-5
      .col-10.col-md-10.col-lg-10.movil(data-aos="fade-right")
        .titulo-sexto.color-acento-contenido
          p.titulo.pb-0.mb-0 #[b Figura 2.] <em>Deberes y responsabilidades de la política de participación social</em>
        figure
          img.mb-3(src='@/assets/curso/temas/tema1/30-m.svg', alt='En la figura 2 se establecen las responsabilidades y deberes de la política de participación social.')
          figcaption Nota. Ministerio de Salud y Protección Social.  Resolución 2063 de 2017.

    p(data-aos="fade-left").mb-5 Además, en la ejecución de la política de participación social, es importante tener en cuenta las responsabilidades y la organización de los diversos actores que están involucrados. En la siguiente tabla, se describen estas participaciones: 

    .titulo-sexto.color-acento-contenido
      p.titulo.pb-0.mb-0 #[b Tabla 2.] <em>Responsabilidades en la ejecución de la participación social</em>
    .tabla-a.color-acento-contenido.mb-5
      table
        caption Nota. Ministerio de Salud y Protección Social.  Resolución 2063 de 2017.
        thead.text-dark
          tr
            th Actor 
              span
                i.fas.fa-arrow-right
              br
              | Características 
              span
                i.fas.fa-arrow-down
                
            th Ministerio de Salud y Protección Social 
            th Entidad Territorial  
            th EPS (Entidad Promotora de Salud)
            th IPS (Institución Prestadora de Salud)
        tbody
          td #[b Nivel de gobierno y/o institución. ] 
            td Nacional 
            td Departamento Distrito Municipio
            td Corresponde al territorio donde opera en relación con el actor específico. Asociación de usuarios.
            td Corresponde al territorio donde opera en relación con el actor específico. Asociación de usuarios.
          tr
            td #[b Competencia.] 
            td Direccionar y garantizar el derecho a la participación social en salud. 
            td Garantizar el derecho a la participación social en salud en el área de influencia, así como ejecutar el seguimiento a todos los actores en   garantía de su cumplimiento.
            td 
              ul.lista-ul
                li 
                  i.lista-ul__vineta
                  | Ejecutar las acciones establecidas en la Resolución 2063 -2017 para garantizar la participación social – PPSS.
                li 
                  i.lista-ul__vineta
                  | Entregar información y cuentas por medio del ente territorial.
                li 
                  i.lista-ul__vineta
                  | Disponer información y dar cuentas en el marco de la política a los usuarios de salud.
            td Llevar a cabo las actividades establecidas por el Minsalud en la Resolución 2063 -2017 para garantizar la participación social – PPSS.
          tr
            td #[b Interacciones.] 
            td Con todos los actores.  
            td Con las entidades municipales, EPS, ESE, IPS, otros modos de participación y organizaciones autónomas. 
            td Con el ente territorial, asociaciones de usuarios y veedurías. 
            td Con las asociaciones de usuarios y veedurías.  

    #t_1_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.1 Principios de participación y responsabilidad social 

    p(data-aos="fade-left") Las actividades de participación cuentan con unas orientaciones de tipo ético-políticas que ayudan a ordenar las acciones en el contexto de la responsabilidad social, así como direccionar el relacionamiento de la ciudadanía con las diversas instancias de participación social en salud. 
    p(data-aos="fade-left").mb-5 Las actividades de participación social en salud se fundamentan en los siguientes principios: 

    .row.justify-content-center.align-items-center.mb-5
      .col-10
        ImagenInfografica.color-acento-botones
          template(v-slot:imagen)
            figure
              img(src='@/assets/curso/temas/tema1/31.svg', alt='Texto que describa la imagen')

          .tarjeta.color-acento-contenido--borde.p-3(x="34%" y="36%" numero="1")
            p Todos los ciudadanos pueden ejercer el derecho a las acciones de participación.

          .tarjeta.color-acento-contenido--borde.p-3(x="42%" y="17%" numero="2")
            p Las acciones de participación social en salud se unen a las dinámicas del territorio con el fin de promover y asegurar el derecho a la participación, lo que involucra identificar el desarrollo diferencial de los espacios, mecanismos e instancias de participación social.

          .tarjeta.color-acento-contenido--borde.p-3(x="58%" y="17%" numero="3")
            p Es la identificación y promoción de la pluralidad, la heterogeneidad y la singularidad de las personas que hagan parte de los procesos de participación. Las acciones de participación deben contar con los siguientes elementos: planos étnicos, lo cultural, de edad, de sexo, de identidad de género u orientación sexual, de religión o en política.

          .tarjeta.color-acento-contenido--borde.p-3(x="66%" y="36%" numero="4")
            p Se refiere a la posibilidad de generar acciones articuladas entre los ciudadanos, las diversas organizaciones e instituciones, por medio de actividades que ayuden en el desarrollo individual y colectivo, permitiendo generar elementos de privilegio para aquellas personas que se encuentren en desventaja manifiesta en la ejecución de su derecho a la participación.

          .tarjeta.color-acento-contenido--borde.p-3(x="66%" y="62.5%" numero="5")
            p Es la posibilidad que tienen las personas y las organizaciones de contar con libertad y dignidad para tener derecho a la participación y promoviendo el pleno uso de la libertad y la promoción de la autodeterminación, tanto a nivel individual como colectivo.

          .tarjeta.color-acento-contenido--borde.p-3(x="58%" y="82%" numero="6")
            p Busca conocer las condiciones de desigualdad que puedan afectar a las personas en el ejercicio de la participación social. En este principio, se deben tener presentes las asimetrías de poder y los varios puntos de vista, con el fin de evitar la discriminación.

          .tarjeta.color-acento-contenido--borde.p-3(x="42%" y="82%" numero="7")
            p Es la creación de mecanismos de acceso a toda la información, así como la comunicación e interacción entre los diversos actores del sistema de salud (funcionarios, trabajadores de la salud y población), en función de las acciones de administrar y gerenciar los recursos públicos, y garantizando el cumplimiento de políticas públicas y programas e impacto en la población.

          .tarjeta.color-acento-contenido--borde.p-3(x="33%" y="62.5%" numero="8")
            p Se refiere a la unión de esfuerzos entre los actores sociales, promoviendo la colaboración protagónica y logrando hacerles frente a las situaciones relacionadas con los procesos de participación social en salud, con el objetivo de impactar en mayor medida la calidad de vida de las personas.

    .row
      .col-lg-6.movil 
        a.anexo.mb-4(:href="obtenerLink('/downloads/principios_participacion_responsabilidad_social.pdf')" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-pdf.svg")
          .anexo__texto
            p Descargar. Principios de participación social.

    #t_1_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.2 Mecanismos democráticos y de participación social

    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema1/32.png')})`}"
      )
      .bloque-texto-g__texto.p-5
        p.mb-0 La Ley estatutaria 1757 de 2015, en el marco de la participación democrática, tiene como objetivo promover, proteger y dar garantía de las diversas modalidades que hay para ejercer el derecho de participar en la supervisión y control del poder político.

    p(data-aos="fade-left") Esta norma regula dichos mecanismos, así como la iniciativa popular y de ámbito normativo ante las entidades públicas, el referendo, la consulta popular, la revocatoria del mandato, el plebiscito y el cabildo abierto; igualmente, regula las normas de la participación democrática de las organizaciones civiles. A continuación, se describen algunos de los mecanismos que se podrán tener en cuenta y ser usados para promover la participación en asuntos relacionados con la salud de las personas.

    p(data-aos="fade-left").mb-5 En cuanto a los mecanismos democráticos establecidos para la participación ciudadana, se encuentran el plebiscito, el referendo, la consulta popular, el cabildo abierto, la iniciativa legislativa y la revocatoria del mandato, entre otros. En la siguiente tabla, se hace una breve descripción de estos.

    .titulo-sexto.color-acento-contenido
      p.titulo.pb-0.mb-0 #[b Tabla 3.] <em>Mecanismos democráticos para la participación ciudadana</em>
    .tabla-a.color-acento-contenido.mb-5
      table
        thead.text-dark
          tr
            th Nombre del mecanismo
            th(colspan="2") Descripción y rango de acción
        tbody
          tr(style="background-color:#F6F6F6")
            td #[b Acciones populares y de grupo]
            td(colspan="2") Mecanismo por medio del cual la persona puede acudir a una autoridad judicial para cuidar y defender todos los intereses a nivel colectivo, logrando garantizar el patrimonio público, el medio ambiente y demás. De acuerdo con el Artículo 48 de la Constitución Política de Colombia, se consideran derechos colectivos: 
              br
              br
              | Derecho al ambiente sano, a la moralidad administrativa, al acceso de los servicios públicos, al aprovechamiento de los recursos naturales, a la utilización y defensa de los bienes de uso público, a la defensa del patrimonio público, al patrimonio cultural de la nación y la seguridad y salubridad pública.
          tr 
            td #[b Acción de cumplimiento]
            td(colspan="2") Es el recurso popular por medio del cual una persona natural o jurídica puede dirigirse ante una autoridad competente, ya sea de tipo legislativo, judicial, administrativa o entidad de supervisión y control, con el fin de hacer cumplir las leyes o actos administrativos. 
          tr(style="background-color:#F6F6F6")
            td #[b Solicitud de información]
            td(colspan="2") Toda persona tiene derecho a solicitar información sobre un tema o entidad; esta información podrá ser por medio de copias o el acceso directo a documentos que se encuentren dentro de la entidad. Debe ser entregada en un plazo no mayor a 10 días hábiles posteriores a la solicitud de la información. Si tal información no puede ser entregada en este plazo, se deben exponer los motivos y se debe dar una fecha estimada de entrega no mayor a 90 días. 
          tr
            td #[b #[em Habeas Data]]
            td(colspan="2") Mecanismo fundamentado en la defensa judicial a la que tiene derecho toda persona, en el marco de la defensa del buen nombre e imagen. El mecanismo cuenta con el derecho de identificar, actualizar y rectificar todo tipo de información que se haya registrado en bases de datos y demás archivos, tanto de entidades públicas como privadas. 
          tr(style="background-color:#F6F6F6")
            td #[b Derechos de petición]
            td(colspan="2") Esta acción puede realizarse de manera verbal o escrita, para solicitar pronta solución a un asunto, ya sea de interés personal o colectivo. El término para que sea respondido es de 15 días hábiles. De no obtener una respuesta, la persona puede solicitar una acción de tutela.
          tr
            td #[b Acción de tutela]
            td(colspan="2") Le permite al ciudadano reclamar la protección inmediata de sus derechos constitucionales mediante el reclamo ante el ente judicial. Para la respuesta ante la acción de tutela, no pueden pasar más de 10 días para su debida solución.
          tr(style="background-color:#F6F6F6")
            td #[b Quejas y reclamos]
            td(colspan="2") Estrategia que le posibilita a los ciudadanos y demás organizaciones de tipo comunitario dar a conocer a la alta dirección de la entidad todas las fallas o anomalías presentadas en el marco de la prestación del servicio por parte de algún funcionario o área.  
          tr
            td #[b Buzón de sugerencias]
            td(colspan="2") Mecanismo que le permite a la persona dar su opinión en el marco de la gestión de la entidad.
          tr(style="background-color:#F6F6F6")
            td #[b Consultas públicas – página web]
            td(colspan="2") Permite entregar y recibir diversos comentarios, sugerencias y demás observaciones, en el marco de la construcción de nuevos proyectos, políticas, planes, programas, y demás normas de competencia relacionadas con el ambiente.
          tr
            td #[b Referendo (vigilancia y control)]
            td(colspan="2") Convocatoria dirigida a los ciudadanos para que puedan aprobar o rechazar algún tipo de proyecto de norma jurídica, o que sea derogada alguna norma que se encuentre vigente. 
          tr(style="background-color:#F6F6F6")
            td #[b Cabildo abierto (vigilancia y control):]
            td(colspan="2") Mecanismo democrático que consiste en la reunión de concejos distritales, municipales y de las juntas administradoras de tipo local, para que los ciudadanos puedan estar inmersos en los temas de asunto común.
          tr
            td #[b Iniciativa popular (vigilancia y control)]
            td(colspan="2") Es un derecho que tienen los grupos de personas de formular y presentar proyectos en el marco del desarrollo de diversas normas (ley, resolución, ordenanza), para que se puedan debatir y se tenga respuesta de aprobación, modificación o negación por la entidad pública competente.
          tr(style="background-color:#F6F6F6")
            td #[b Audiencias públicas (vigilancia y control)]
            td(colspan="2") Se hacen con el fin de evaluar la formulación, ejecución o valoración de diversas políticas y programas a cargo de una entidad; en conclusión, este mecanismo sirve para conocer y discutir los resultados de la operación de los proyectos.
          tr
            td #[b Veedurías ciudadanas (vigilancia y control)]
            td(colspan="2") Estrategia que le permite a los ciudadanos realizar supervisión, en todo el proceso de gestión pública o vigilancia, a una entidad encargada de la prestación de servicios. 

    .row.justify-content-center.align-items-center.mb-5
      .col-7 
        p Por otro lado, en los mecanismos de participación, y en concordancia con lo dispuesto en el #[b Decreto 1757 de 1994], el cual fue actualizado mediante el #[b Decreto 1616 de 1995], los mecanismos de participación en la prestación de los servicios se enfocan en la participación social, y esta, a su vez, en la participación en las instituciones del Sistema General de Seguridad Social en Salud -SGSSS. En este sentido, la participación social se orienta en dos líneas: la ciudadana y la comunitaria; es en sí misma responsable del proceso de interacción de tipo social que tiene como objetivo realizar intervención en las diversas decisiones de salud, que responde a los intereses de tipo individual y colectivo en relación con la gestión y ejecución de los procesos. La participación basa sus fundamentos en principios de solidaridad, equidad y universalidad, con el fin de aportar al bienestar humano y desarrollo social. 
        p En cuanto a las acciones de participación social, existe un compromiso, ya sea de tipo individual o colectivo, para asumir la responsabilidad por las diversas problemáticas en cuestión de salud y, asimismo, darle oportuna solución. 
        p Las acciones en participación social se describen a continuación:
      .col-5
        img(src='@/assets/curso/temas/tema1/33.png')

    .row(data-aos="fade-left").mb-5
      .col-sm-6.col-lg-4.mb-4.mb-lg-0
        .tarjeta--boton.color-primario.p-4(style='height:100%')
          .row.justify-content-center.mb-3
            .col-7
              figure
                img(src='@/assets/curso/temas/tema1/34.svg', alt='Texto que describa la imagen')

          h3.text-center Participación ciudadana
          p Espacio donde se exponen los deberes y derechos de la persona, con el objetivo de favorecer la conservación de la salud a nivel personal, familiar y comunitaria, y asimismo contribuir en la planeación, puesta en marcha, evaluación y seguimiento de los servicios de salud. 
          p Para llevar a cabo la práctica de este tipo de participación, se puede contar con: 
          
          ul.lista-ul
            li 
              i.lista-ul__vineta
              | Servicio de atención a los usuarios. 
            li 
              i.lista-ul__vineta
              | Servicio de atención a la comunidad. 
            li 
              i.lista-ul__vineta
              | Sistema de atención e información a usuarios.

      .col-sm-6.col-lg-4.mb-4.mb-lg-0
        .tarjeta--boton.color-primario.p-4(style='height:100%')
          .row.justify-content-center.mb-3
            .col-7
              figure
                img(src='@/assets/curso/temas/tema1/35.svg', alt='Texto que describa la imagen')

          h3.text-center Participación comunitaria
          p Derecho de las organizaciones comunitarias para ejercer voz y voto alrededor de: planeación, gestión, evaluación y supervisión en salud. Se define la participación comunitaria como el proceso por el que las personas y familias son responsables de su salud y bienestar, junto con sus comunidades, contribuyendo en el desarrollo de todos.
          p Este proceso debe ser dinámico y permanente, mediante los Comités de Participación Comunitaria en Salud, COPACOS. Estos espacios de comunicación y concertación agrupan diversos actores sociales y del Estado.

      .col-sm-6.col-lg-4.mb-4.mb-sm-0
        .tarjeta--boton.color-primario.p-4(style='height:100%')
          .row.justify-content-center.mb-3
            .col-7
              figure
                img(src='@/assets/curso/temas/tema1/36.svg', alt='Texto que describa la imagen')

          h3.text-center Participación en las instituciones del Sistema General de Seguridad Social en Salud
          p Este tipo de participación es el resultado de la interrelación entre usuario, funcionarios públicos y privados para el seguimiento de la valoración, gestión y acciones de mejoramiento en la prestación del servicio público de salud. Las instituciones que hacen parte del Sistema General de Seguridad Social en Salud, deben dar seguridad sobre la participación ciudadana, comunitaria y social en todas las áreas que corresponda, mediante la alianza con la asociación de usuarios y/o con los comités de ética hospitalaria.

    p(data-aos="fade-left").mb-5 El Ministerio de Salud y Protección Social determina que, para el ejercicio de la participación social de forma adecuada, deben considerarse varios aspectos y escenarios de participación. 

    .BGIMG02.p-4.p-md-5.mb-5
      .row.justify-content-around.align-items-center
        .col-1.col-sm-1.col-md-1.mb-4.mb-md-0
          img(src="@/assets/curso/temas/tema1/37.svg")

        .col-md.col-lg-9
          h3 Le invitamos a consultar en el material complementario el correspondiente a los Lineamientos de participación ciudadana.
          p.mb-4 Este documento informa sobre los diferentes mecanismos de participación que se han regulado desde el Ministerio de Salud y de la Protección Social, indicando además los escenarios donde se han de llevar a cabo, mediante preguntas orientadoras para su comprensión.
        .col-md.col-lg-2
          a.boton.color-acento-botones.texto-blanco(href=('https://www.minsalud.gov.co/sites/rid/Lists/BibliotecaDigital/RIDE/VS/PP/SA/15documento-salud-ambiental-participacion-social.pdf') target="_blank" type="application/pdf")
            span Descargar
            i.fas.fa-file-download

    #t_1_3.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.3 Promover el empoderamiento y la gobernanza

    p(data-aos="fade-left").mb-5 Cuando se hace referencia al término de participación ciudadana, se debe tener presente que este tiene relación con las acciones de democracia y de empoderamiento. La participación lleva implícito el concepto de empoderamiento, ya que ambos incluyen aspectos relacionados con procesos de toma de decisiones e incidencia en las acciones a seguir en el marco de un objetivo común o individual. 

    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema1/38.png')})`}"
      )
      .bloque-texto-g__texto.p-5
        p.mb-0 El empoderamiento influye en la gestión local, la cual es la puesta en práctica de todas las acciones en pro de tener una formación en el contexto participativo. Asimismo, se puede decir que el empoderamiento es un proceso que ayuda a potenciar y fortalecer el capital social, logrando de esta manera que las diversas organizaciones puedan aumentar las acciones de participación y la toma de decisiones para la solución de los problemas que los afectan, ayudando a mejorar las capacidades de intervención, control, planificación y priorización en el marco de todas las actividades desarrolladas por las diversas entidades.

    p(data-aos="fade-left") Se puede decir que la gestión local hace parte integral del proceso de empoderamiento y contribuye en el desarrollo local, así como en la estimulación de los procesos de participación ciudadana desde los contextos macro y micro, logrando conocer y potenciar las características del territorio y de las personas que lo habitan, para que luego se pueda empezar a tener provecho de esas potencialidades; adicionalmente a esto, contribuye en la reconstrucción del tejido social, que es la base de todo el proceso de participación social en salud. 
    p(data-aos="fade-left") La acción de dinamizar el tejido social consiste en generar una comunicación permanente de construcción e interacción entre grupos ya existentes y organizados y con nuevos actores sociales, lo que permite la constante agregación de personas al proceso de empoderamiento en torno a las necesidades y propuestas concretas. Además, posibilita que se generen acciones de deliberación colectiva, logrando, por medio de esta discusión, que todos los actores involucrados puedan presentar sus expectativas y necesidades, teniendo claro que se deben evitar en todo momento las asimetrías de poderes entre los ciudadanos y aquellas entidades que gobiernan y tienen a su cargo la dirección y control de los diversos procesos inmersos en la prestación de servicios de salud.  
    p(data-aos="fade-left").mb-5 Además de lo anterior, los procesos de empoderamiento permiten que la diversidad social se vea reflejada en los procesos participativos, permitiendo conocer un amplio número de propuestas y visiones, lo que ayuda en el fortalecimiento de los argumentos para el debate político. El empoderamiento y las acciones de gobernanza permiten generar espacios de inclusión social, donde pueden interactuar las diferencias de opinión y, de esta manera, lograr vínculos efectivos entre los ciudadanos y las entidades gubernamentales y demás actores del sistema. 

    .tarjeta.color-secundario2.p-4(style="border-radius:0").mb-5
      .row.justify-content-center.align-items-center
        .col-6 
          p El empoderamiento y la gobernanza aportan fundamentalmente en la participación social en salud.  Permiten el debate público y la contraposición de posturas, donde los ciudadanos pueden desarrollar una mejor comprensión de sus intereses y necesidades en relación con el bien común, haciendo énfasis en las acciones concluyentes alrededor de los intereses propios y de los demás, teniendo que definir prioridades de una manera respetuosa, articulada y democrática. Estas acciones de evaluación entre los intereses personales y los colectivos permiten un aprendizaje continuo, que fortalece a la comunidad convirtiéndola en agentes de cambio, que enfocan sus objetivos en la definición colectiva del bien común, en este caso, que garantice la salud y calidad en todos los procesos de atención en el marco del Sistema General de Seguridad Social en Salud y sus líneas de salud pública y, por ende, de la salud ambiental. 
        .col-4
          img(src='@/assets/curso/temas/tema1/39.png')

</template>

<script>
export default {
  name: 'Tema1',
  components: {},
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
