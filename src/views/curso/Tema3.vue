<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'3. Factores de relacionados en la seguridad vial laboral'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden
    .bg-color-7.mb-5(data-aos="fade-up")
      .row.justify-content-center.align-items-center            
        .col-lg.mb-3.mb-lg-0
          .p-4
            p.mb-0(data-aos="fade-up") La seguridad vial laboral es esencial para proteger la integridad de los trabajadores y garantizar la continuidad operativa. Dos actores fundamentales son el vehículo y el conductor, cuyos factores asociados deben gestionarse adecuadamente.
        .col-lg-auto
          figure
            img.img-a.img-t(src='@/assets/curso/temas/24.png', alt='') 

    h3(data-aos="fade-down") Vehículo
    p(data-aos="fade-down") La gestión segura del vehículo, implica inspecciones, mantenimiento preventivo y alineación con normativas. A continuación se resumen los aspectos principales:

    .row.align-items-start.mb-5
      .col-lg-4.mb-3.mb-lg-0 
        figure
          img.img-a.img-t(src="@/assets/curso/temas/25.png", alt="")        
      .col-lg-8
        AcordionA(tipo="b")
          .div(titulo="Inspecciones Diarias (Resolución 40595/2022, pasos 16 y 17)")
            p Toda organización debe establecer procedimientos para inspeccionar vehículos motorizados y no motorizados utilizados en desplazamientos laborales. Deben incluir:
            ul.lista-ul--color.mb-0            
              li.d-flex
                i.far.fa-arrow-alt-circle-right.color-1
                p.mb-0 Responsables designados. 
              li.d-flex
                i.far.fa-arrow-alt-circle-right.color-1
                p.mb-0 Formato de verificación técnica (estado, seguridad, elementos de protección). 
              li.d-flex
                i.far.fa-arrow-alt-circle-right.color-1
                p.mb-0 #[b Documentación:] licencia de tránsito, SOAT, revisión técnico-mecánica, licencia de conducción. 
              li.d-flex
                i.far.fa-arrow-alt-circle-right.color-1
                p.mb-0 #[b Condiciones:] luces, neumáticos, fluidos, limpia brisas, espejos. 
              li.d-flex
                i.far.fa-arrow-alt-circle-right.color-1
                p.mb-0 #[b Equipos:] cinturón de seguridad, extintor, botiquín, señal de pare, llanta de repuesto, casco (motociclistas).              
          .div(titulo="Buenas prácticas complementarias")
            p Inspecciones al final de la jornada, tras recorridos prolongados o cambios de conductor. Uso de alertas para vencimientos de documentos o mantenimientos.   
          .div(titulo="Plan de mantenimiento preventivo")
            ul.lista-ul--color.mb-0            
              li.d-flex
                i.far.fa-arrow-alt-circle-right.color-1
                p.mb-0 #[b Considera:] observaciones de inspecciones, condiciones inseguras, recomendaciones del fabricante, riesgos operativos. 
              li.d-flex
                i.far.fa-arrow-alt-circle-right.color-1
                p.mb-0 #[b Hoja de vida técnica del vehículo:] adquisiciones, reparaciones, mantenimientos, piezas reemplazadas, técnicos involucrados. 
              li.d-flex
                i.far.fa-arrow-alt-circle-right.color-1
                p.mb-0 Incluye también vehículos personales utilizados en actividades laborales.                
          .div(titulo="Marco normativo relacionado")
            ul.lista-ul--color.mb-0            
              li.d-flex
                i.far.fa-arrow-alt-circle-right.color-1
                p.mb-0 Artículo 2.2.4.6.24 del Decreto 1072 del 2015. 
              li.d-flex
                i.far.fa-arrow-alt-circle-right.color-1
                p.mb-0 Numeral 8.1 de la norma ISO 39001. 
              li.d-flex
                i.far.fa-arrow-alt-circle-right.color-1
                p.mb-0 Ambos promueven el mantenimiento planificado como control operativo esencial. 

    h3(data-aos="fade-down") Conductor
    p(data-aos="fade-down") A continuación, se presenta un análisis sobre el rol del conductor en la prevención de siniestros viales, destacando los factores físicos, emocionales y conductuales que inciden en la seguridad, así como las estrategias clave para su gestión efectiva.


    .bg-full-width.bg-fondo-slider.mb-5(data-aos="fade-left")
      .p-4.p-md-5
        figure
          .video
            iframe(width="560" height="315" src="https://www.youtube.com/embed/E_fZRzOD6bE?si=3GE4DTRlIaZUg2-D" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen) 

    h3(data-aos="fade-down") Gestión organizacional 
    p(data-aos="fade-down") Este componente articula requisitos de contratación, funciones, evaluación y cultura de seguridad para lograr una operación segura y responsable. 
    .bg-full-width.bg-fondo-slider.mb-5(data-aos="fade-right")
      .p-4.p-md-5
        SlyderA(tipo="b").bg-white
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img.img-a.img-t(src="@/assets/curso/temas/26.png")               
            .col-lg-7
              h5 Contratación y selección (Resolución 40595/2022, paso 10)
              ul.lista-ul--color.mb-0            
                li.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Pruebas teóricas y prácticas. 
                li.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Exámenes médicos ocupacionales. 
                li.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Validación de licencias y antecedentes viales.
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img.img-a.img-t(src="@/assets/curso/temas/27.png")               
            .col-lg-7
              h5 Funciones y responsabilidades
              ul.lista-ul--color.mb-0            
                li.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Reportar siniestros. 
                li.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Participar en capacitaciones. 
                li.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Cumplir normativas viales y del PESV. 
                li.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Informar sobre su estado de salud. 
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img.img-a.img-t(src="@/assets/curso/temas/28.png")               
            .col-lg-7
              h5 Evaluación del comportamiento anual
              ul.lista-ul--color.mb-0            
                li.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Registro de siniestros e infracciones.
                li.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Quejas por conductas riesgosas.
                li.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Capacitaciones recibidas. 
                li.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Esta evaluación permite identificar necesidades de refuerzo formativo. 
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img.img-a.img-t(src="@/assets/curso/temas/29.png")               
            .col-lg-7
              h5 Formación y cultura de seguridad (Modelo de la Curva de Bradley) 
              p Evolución de la conducta del conductor:                                           
              ul.lista-ul--color.mb-0            
                li.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Reactiva. 
                li.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Dependiente. 
                li.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Independiente. 
                li.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Interdependiente         

              p Se promueve una actitud solidaria y preventiva, basada en la conciencia y responsabilidad compartida.

    h3(data-aos="fade-down") Entorno
    p(data-aos="fade-down") El entorno vial, tanto externo como inmediato a los lugares de trabajo, influye en la siniestralidad y debe ser identificado, evaluado y adaptado continuamente.
    
    .row.align-items-start.mb-5
      .col-lg-4.mb-3.mb-lg-0 
        figure
          img.img-a.img-t(src="@/assets/curso/temas/30.png", alt="")        
      .col-lg-8
        AcordionA(tipo="b")
          .div(titulo="Condiciones de la vía")
            ul.lista-ul--color.mb-0            
              li.d-flex
                i.far.fa-arrow-alt-circle-right.color-1
                p.mb-0 Pavimento deteriorado (baches, grietas, desniveles).
              li.d-flex
                i.far.fa-arrow-alt-circle-right.color-1
                p.mb-0 Señalización deficiente o ausente.
              li.d-flex
                i.far.fa-arrow-alt-circle-right.color-1
                p.mb-0 Iluminación insuficiente.
              li.d-flex
                i.far.fa-arrow-alt-circle-right.color-1
                p.mb-0 Obstáculos como escombros, vegetación o vehículos mal ubicados. 
          .div(titulo="Infraestructura vial")
            ul.lista-ul--color.mb-0            
              li.d-flex
                i.far.fa-arrow-alt-circle-right.color-1
                p.mb-0 Curvas, intersecciones y rotondas bien diseñadas.
              li.d-flex
                i.far.fa-arrow-alt-circle-right.color-1
                p.mb-0 Zonas de cruce, ciclovías y rampas bien delimitadas.
              li.d-flex
                i.far.fa-arrow-alt-circle-right.color-1
                p.mb-0 Áreas logísticas que no interfieran con rutas principales. 
          .div(titulo="Condiciones climáticas")
            ul.lista-ul--color.mb-0            
              li.d-flex
                i.far.fa-arrow-alt-circle-right.color-1
                p.mb-0 Lluvia, niebla, viento cruzado, altas temperaturas.
              li.d-flex
                i.far.fa-arrow-alt-circle-right.color-1
                p.mb-0 Estas afectan visibilidad, adherencia y reacción del conductor.

          .div(titulo="Entorno Urbano vs. Rural")
            ul.lista-ul--color.mb-0            
              li.d-flex
                i.far.fa-arrow-alt-circle-right.color-1
                p.mb-0 Urbano: alta densidad vehicular, intersecciones complejas.
              li.d-flex
                i.far.fa-arrow-alt-circle-right.color-1
                p.mb-0 Rural: iluminación escasa, señalización pobre, animales o maquinaria en la vía.                               
            

    .row.align-items-start.mb-5      
      .col-lg-8.mb-3.mb-lg-0 
        AcordionA(tipo="b")
          .div(titulo="Zonas internas de trabajo")
            ul.lista-ul--color.mb-0            
              li.d-flex
                i.far.fa-arrow-alt-circle-right.color-1
                p.mb-0 Rutas de tránsito internas, estacionamientos y zonas de maniobra bien señalizados y organizados.
          .div(titulo="Factores externos no controlables")
            ul.lista-ul--color.mb-0            
              li.d-flex
                i.far.fa-arrow-alt-circle-right.color-1
                p.mb-0 Obras, eventos masivos, actividades agrícolas o industriales cercanas. 
          .div(titulo="Transporte de carga")
            ul.lista-ul--color.mb-0            
              li.d-flex
                i.far.fa-arrow-alt-circle-right.color-1
                p.mb-0 Distribución adecuada de la carga.
              li.d-flex
                i.far.fa-arrow-alt-circle-right.color-1
                p.mb-0 Compatibilidad ruta-vehículo.
              li.d-flex
                i.far.fa-arrow-alt-circle-right.color-1
                p.mb-0 Revisión técnica de componentes críticos. 
      .col-lg-4
        figure
          img.img-a.img-t(src="@/assets/curso/temas/31.png", alt="")   

    h3(data-aos="fade-down") Organización
    p(data-aos="fade-down") La organización es responsable de diseñar e implementar estrategias que garanticen entornos seguros, normas claras y una cultura de prevención sostenible.

    .bg-full-width.bg-color-info.mb-5
      .p-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-10
            ImagenInfografica.color-secundario
                template(v-slot:imagen)
                  figure
                    img(src='@/assets/curso/temas/32.png', alt='', style="max-width: 1106px;").mx-auto

                .bg-color-white.box-shadow.p-3(x="2.4%" y="35.8%" numero="+")
                  h5 Gestión de rutas y horarios            
                  p.mb-0 Reducción de riesgos por fatiga, congestión o trayectos peligrosos. 
                .bg-color-white.box-shadow.p-3(x="9.4%" y="62.6%" numero="+")
                  h5 Cultura organizacional             
                  p.mb-0 Comunicación abierta, reporte de riesgos, compromiso con la vida y el bienestar.   
                .bg-color-white.box-shadow.p-3(x="5.4%" y="79.6%" numero="+")
                  h5 Gestión del tiempo y carga de trabajo            
                  p.mb-0  Prevención del agotamiento y mejora del rendimiento del conductor.  
                .bg-color-white.box-shadow.p-3(x="88.5%" y="13.2%" numero="+")
                  h5 Supervisión y control             
                  p.mb-0 Uso de telemetría y monitoreo para detectar y corregir conductas de riesgo.   
                .bg-color-white.box-shadow.p-3(x="97.6%" y="28.2%" numero="+")
                  h5 Recursos y mantenimiento             
                  p.mb-0 Provisión de equipos, tecnología, señalización y condiciones de circulación óptimas.   
                .bg-color-white.box-shadow.p-3(x="97.6%" y="50.1%" numero="+")
                  h5 Políticas y procedimientos             
                  p.mb-0 Establecen normas claras sobre movilidad, roles y responsabilidades.  
                .bg-color-white.box-shadow.p-3(x="88.5%" y="64.7%" numero="+")
                  h5 Capacitación y conciencia             
                  p.mb-0 Programas educativos que refuerzan conocimientos y fomentan actitudes seguras. 


    .bg-full-width.border-top.color-primario
      .p-4.p-md-5
        h2(data-aos="fade-left") MATERIAL COMPLEMENTARIO
        .row.material-complementario
          .col-12.col-md-6.col-lg-7
            p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://safetya.co/estructura-del-plan-estrategico-de-seguridad-vial/" target="_blank" rel="noopener noreferrer") SafetYA. (2016). Estructura del Plan Estratégico de Seguridad Vial.  

            p.d-flex.my-4
              img.me-3(src='@/assets/template/book.svg' :style="{'max-width':'16px'}")
              a(href="https://mintransporte.gov.co/ " target="_blank" rel="noopener noreferrer") Mintransporte. (s f.). Ministerio de Transporte. 


            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://open.spotify.com/show/3XpEsfYr1EXSy60xPFfK5s?si=7a11ae03dd454bad" target="_blank" rel="noopener noreferrer") Spotify. (s.f.). 

          .col-12.col-md-6.col-lg-3.offset-lg-1
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='')
  
</template>

<script>
export default {
  name: 'Tema3',
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass"></style>
