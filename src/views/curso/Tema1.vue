<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'1. Implementación y control de medidas de seguridad vial laboral'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden
    .bg-color-4.mb-5(data-aos="fade-up")
      .row.justify-content-center.align-items-center            
        .col-lg.mb-3.mb-lg-0
          .p-4
            p.mb-0(data-aos="fade-up") La implementación y control de medidas de seguridad vial laboral, son fundamentales para proteger a los trabajadores que deben desplazarse en el ejercicio de sus funciones. Su objetivo principal es reducir los riesgos asociados a los desplazamientos laborales, fomentando un entorno de trabajo seguro, saludable y responsable.
        .col-lg-auto
          figure
            img.img-a.img-t(src='@/assets/curso/temas/2.png', alt='')  

    h3(data-aos="fade-down") Enfoque Integral
    p(data-aos="fade-down") La seguridad vial en el ámbito laboral no se limita a cumplir normativas, sino que implica la promoción de una cultura preventiva y de responsabilidad compartida entre empleadores y trabajadores. Para ello, se requiere una combinación de acciones formativas, tecnológicas, sociales y organizacionales que refuercen el compromiso colectivo. Los elementos clave en la seguridad vial laboral son: 
    
    .bg-full-width-2.bg-fondo-1
      .px-4.px-md-5.pb-md-3
        .row.justify-content-center.mb-5 
          .col-lg-4.mb-3.mb-lg-0 
            figure
              img.img-a.img-t(src='@/assets/curso/temas/3.png', alt='')   

          .col-lg-8
            SlyderF.text-center(columnas="col-12 col-lg-6")
              .bg-color-white.p-4.h-100.sha.brounded-sm
                img(src='@/assets/curso/temas/4.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.mb-4 Formativa
                p Capacitación continua, campañas de sensibilización, conocimiento de normativas internas.  
              .bg-color-white.p-4.h-100.sha.brounded-sm
                img(src='@/assets/curso/temas/5.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.mb-4 Técnica
                p Uso de GPS, dispositivos de seguridad vehicular, mantenimiento preventivo.
              .bg-color-white.p-4.h-100.sha.brounded-sm
                img(src='@/assets/curso/temas/6.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.mb-4 Organizacional
                p Planificación de rutas seguras, políticas de descanso, controles administrativos.
              .bg-color-white.p-4.h-100.sha.brounded-sm
                img(src='@/assets/curso/temas/7.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.mb-4 Social
                p Participación de empleadores, trabajadores y sindicatos, en campañas de concientización.
              .bg-color-white.p-4.h-100.sha.brounded-sm
                img(src='@/assets/curso/temas/8.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.mb-4 Analítica
                p Análisis de datos e incidentes, para prevenir riesgos y optimizar recursos.

        .row.mb-5
          .col-lg-4.mb-3.mb-lg-0 
            figure
              img.img-a.img-t(src="@/assets/curso/temas/9.png", data-aos="zoom-in")                 
          .col-lg-8.j1
            h3(data-aos="fade-down") Rol de la tecnología y la gestión
            p(data-aos="fade-down") Desde el punto de vista técnico, es crucial el uso de herramientas de monitoreo y control como los sistemas GPS, los registros digitales de incidentes y los dispositivos de seguridad, instalados en los vehículos. Estas herramientas permiten detectar vulnerabilidades, aplicar medidas correctivas y mejorar continuamente, las condiciones de los desplazamientos laborales. 
            h3(data-aos="fade-down") Cultura organizacional y compromiso social
            p(data-aos="fade-down") La seguridad vial laboral, está íntimamente relacionada con la cultura organizacional. Fomentar una actitud preventiva, promover el respeto por las normas de tránsito y asumir un compromiso colectivo contribuye a disminuir la incidencia de accidentes. Las buenas prácticas internas y la colaboración entre todos los actores laborales consolidan un entorno más seguro.
            h3(data-aos="fade-down") Responsabilidad compartida
            p(data-aos="fade-down") La implementación y control de estas medidas no es competencia exclusiva del Estado. Se requiere la participación activa de empresas, instituciones educativas y organizaciones civiles en la adopción de políticas eficaces, la aplicación de protocolos y la evaluación constante de resultados. Solo mediante un esfuerzo coordinado y sostenido se podrá proteger la integridad de los trabajadores y promover un desarrollo social y económico sostenible.                         

               

        .row.mb-5           
          .col-lg-8.mb-3.mb-lg-0.j1 
            h3(data-aos="fade-down") Implementación y ejecución del plan estratégico de seguridad vial
            p(data-aos="fade-down") La implementación y ejecución del plan estratégico de seguridad vial, constituyen etapas fundamentales para convertir las políticas y lineamientos, en acciones concretas, que contribuyan a reducir la siniestralidad, mejorar la movilidad y proteger la vida de todos los usuarios de las vías públicas. Este proceso demanda una planificación meticulosa, coordinación interinstitucional y un compromiso sostenido de diversos actores: entidades gubernamentales, instituciones de tránsito, organizaciones civiles, sector privado y ciudadanía en general.

          .col-lg-4
            figure
              img.img-a.img-t(src="@/assets/curso/temas/10.png", data-aos="zoom-in")  


    .bg-full-width.bg-color-5.p-4.mb-4(data-aos="fade-left")
      .px-4
        .row.align-items-center
          .col-lg-auto
            img.img-a.img-t(src="@/assets/curso/temas/14.png")
          .col-lg
            p El primer paso para una ejecución efectiva consiste en traducir las metas y objetivos definidos en la fase de diseño en acciones operativas específicas, que cuenten con responsables claros, recursos adecuados y plazos bien definidos. La implementación incluye:
            ul.lista-ul--color            
              li.d-flex
                i.far.fa-arrow-alt-circle-right.color-1
                p.mb-0 Campañas de sensibilización.
              li.d-flex
                i.far.fa-arrow-alt-circle-right.color-1
                p.mb-0 Mejora de la infraestructura vial.
              li.d-flex
                i.far.fa-arrow-alt-circle-right.color-1
                p.mb-0 Fiscalización rigurosa del cumplimiento normativo.
              li.d-flex
                i.far.fa-arrow-alt-circle-right.color-1
                p.mb-0 Incorporación de tecnologías innovadoras para el monitoreo y gestión del tránsito.
              
    p(data-aos="fade-down") Además, es esencial fomentar una cultura de seguridad vial, promoviendo comportamientos responsables y conscientes por parte de todos los actores viales. La ejecución del plan debe mantenerse flexible y adaptativa, ajustándose a condiciones cambiantes. Para ello, se requiere una supervisión periódica, así como la evaluación de resultados mediante indicadores específicos, que permitan:   

    .row.justify-content-center.mb-5           
      .col-lg-4.mb-3.mb-lg-0
        .bg-color-6.h-100.p-3
          .row        
            .col-lg-auto
              img.img-a.img-t(src="@/assets/curso/temas/21.svg")
            .col-lg        
              h5(data-aos="fade-down") 01                           
              p.mb-0(data-aos="fade-up") Identificar áreas de oportunidad.
      .col-lg-4.mb-3.mb-lg-0
        .bg-color-6.h-100.p-3
          .row        
            .col-lg-auto
              img.img-a.img-t(src="@/assets/curso/temas/22.svg")
            .col-lg        
              h5(data-aos="fade-down") 02                           
              p.mb-0(data-aos="fade-up") Corregir desviaciones.
      .col-lg-4.mb-3.mb-lg-0
        .bg-color-6.h-100.p-3
          .row
            .col-lg-auto
              img.img-a.img-t(src="@/assets/curso/temas/23.svg")
            .col-lg
              h5(data-aos="fade-down") 03                          
              p.mb-0(data-aos="fade-up") Optimizar acciones en tiempo real.

    .row.mb-5
      .col-lg-4.mb-3.mb-lg-0
        figure
          img.img-a.img-t(src="@/assets/curso/temas/11.png", data-aos="zoom-in")      
      .col-lg-8.j1
        p(data-aos="fade-left") La comunicación efectiva y la participación activa de la comunidad, son pilares claves para fortalecer el compromiso social y asegurar un impacto positivo y duradero.

        .bg-color-1.p-4(data-aos="fade-left")
          p.mb-0 Finalmente, este proceso no es una tarea aislada, sino un esfuerzo continuo que exige #[b liderazgo, coordinación y visión integral.] Solo a través de una acción conjunta se podrán alcanzar los objetivos del plan, promoviendo un entorno vial más seguro, eficiente y humano para toda la sociedad.

    .bg-full-width.border-top.color-primario
      .p-4.p-md-5
        h2(data-aos="fade-left") MATERIAL COMPLEMENTARIO
        .row.material-complementario
          .col-12.col-md-6.col-lg-7
            p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://mintransporte.gov.co/publicaciones/2942/seguridad-vial/" target="_blank" rel="noopener noreferrer") Ministerio de Transporte. (2014). Seguridad vial. 

            p.d-flex.my-4
              img.me-3(src='@/assets/template/book.svg' :style="{'max-width':'16px'}")
              a(href="https://www.movilidadbogota.gov.co/web/" target="_blank" rel="noopener noreferrer") Secretaría de Movilidad. (s.f.). Secretaría de Movilidad. 


            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://open.spotify.com/show/1HDGyC9yrho7cK2RL3r4Lf?si=21aacd3d7b38491d" target="_blank" rel="noopener noreferrer") Spotify. (s.f.). 

          .col-12.col-md-6.col-lg-3.offset-lg-1
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='')

</template>

<script>
export default {
  name: 'Tema1',
  data: () => ({}),

  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass"></style>
