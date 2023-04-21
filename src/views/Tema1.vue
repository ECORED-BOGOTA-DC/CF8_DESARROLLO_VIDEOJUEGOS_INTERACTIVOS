<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span.text-white 1
      h1 Metodologías de desarrollo
    
    p.mb-5 Son un conjunto de métodos y técnicas con el objetivo de organizar los equipos de trabajo para diseñar soluciones y desarrollar las funciones de un programa de una manera organizada y eficiente.

    .col-lg-10.d-flex.flex-wrap.align-items-center.mb-5.mx-auto
      .col-lg-6.pe-lg-3.order-2.order-lg-1
        h4.mb-4 Metodología rígida
        p Anteriormente para el desarrollo de un proyecto de software se utilizaba una metodología muy rígida en la que se llevaban a cabo procesos de identificación de necesidades, análisis y diseño, planificación, codificación, prueba piloto e implementación; fases que todavía se aplican pero que exigían grandes esfuerzos y se invertía muchísimo tiempo sobre todo en la etapa de planificación donde se debía documentar hasta el más mínimo detalle.
      img.order-1.order-lg-2.mb-4.mb-lg-0.col-lg-6.mx-auto.mb-auto(src="@/assets/curso/temas/tema1/img-1.svg" style="max-width: 505px;")

    .col-lg-10.d-flex.flex-wrap.align-items-center.mb-5.mx-auto
      img.mb-4.mb-lg-0.col-lg-6.mx-auto.mb-auto(src="@/assets/curso/temas/tema1/img-2.svg" style="max-width: 505px;")
      .col-lg-6.ps-lg-3
        h4.mb-4 Reprocesos
        p Toda esta rigurosidad se sustentaba en el argumento de que no se tuviera que hacer ningún reproceso y el producto liberado fuera de alta calidad. Entonces, con la cantidad de tiempo invertido se hacía casi imposible realizar modificaciones en los requisitos, pues tocaba empezar de cero con el levantamiento de la información, la planificación y la documentación para diseñar y desarrollar el producto nuevamente.

    .col-lg-10.d-flex.flex-wrap.align-items-center.mb-5.mx-auto
      .col-lg-6.pe-lg-3.order-2.order-lg-1
        h4.mb-4 Metodologías ágiles
        p Cuando se emprendían proyectos de desarrollo de software mucho más pequeños que exigían tiempos de respuesta cortos para la obtención de resultados, esta metodología se tornó completamente ineficiente pues se gastaba mucho tiempo y recursos en cada fase del proyecto y no se podían realizar cambios a los requisitos para mejorar el producto, por lo tanto empezaron a surgir nuevos métodos más ágiles con un enfoque iterativo es decir por bloques de tareas para llevar a cabo los requisitos de los usuarios teniendo en cuenta que estos pueden cambiar durante todo el proceso de desarrollo.
      img.order-1.order-lg-2.mb-4.mb-lg-0.col-lg-6.mx-auto.mb-auto(src="@/assets/curso/temas/tema1/img-3.svg" style="max-width: 505px;")

    Separador

    .titulo-segundo.color-acento-contenido
      h2#t_1_1 1.1 Metodologías ágiles
    p.mb-5 Como se mencionó anteriormene, las metodologías ágiles surgieron de la necesidad de proporcionar respuestas rápidas a los requerimientos de los proyectos, manteniendo flexibilidad frente a los cambios que puedan surgir o se puedan generar durante el proceso de desarrollo.

    .d-flex.flex-wrap.mb-5
      img.col-lg-6.mx-auto.mb-auto(src="@/assets/curso/temas/tema1/img-4.jpg" style="max-width: 610px;")    
      .col-lg-6
        .bloque-texto-b.color-secundario.p-4.mb-4
          .bloque-texto-b__texto
            i.fas.fa-quote-left
            p.mb-0 Se utilizan para gestionar proyectos donde el cliente no tiene claro todos los requisitos de este y por lo tanto no se puede definir el alcance desde el principio, igualmente cuando durante el desarrollo se cambia de opinión o se adicionan más requisitos.
            i.fas.fa-quote-right
        p.mb-5.ps-lg-4 Estas metodologías no solamente se utilizan en el sector de las TIC para el desarrollo de software y sistemas de información, también se pueden aplicar a cualquier sector productivo, proyecto que se quiera emprender o entorno donde se produzcan cambios de forma frecuente.
          br
          br
          |Existen aspectos muy marcados de las metodologías ágiles respecto a las metodologías tradicionales que dejan entrever sus características, ver tabla 1:
    
    .titulo-sexto.color-acento-contenido
      h5 Tabla 1.
      span Metodologías ágiles vs Metodologías tradicionales
    
    .tabla-b.color-acento-contenido.mb-5
      .tabla-b__header.d-flex.justify-content-around
        h4.mb-0.text-white.col-4.text-end Metodologías Ágiles
        h4.mb-0.text-white.col-4.text-center VS
        h4.mb-0.text-white.col-4.text-start Metodologías Tradicionales
      table
        tr
          td Se enfoca en las personas
          td Se enfoca en los procesos
        tr
          td El cliente participa en todas las fases del proyecto
          td El cliente solo participa al inicio del proyecto
        tr
          td El equipo trabaja colaborativamente
          td Cada miembro del equipo desarrolla una tarea
        tr
          td Trabaja con proyectos medianos y pequeños
          td Trabaja con cualquier proyecto independientemente del tamaño que sea
        tr
          td Lleva a cabo los cambios en los requisitos durante todo el proceso
          td No lleva a cabo ningún cambio en los requisitos durante el proceso
        tr
          td Planifica los requisitos del proyecto en una lista de iteraciones (tareas) para realizar en corto tiempo, luego el desarrollo es iterativo
          td Planifica los requisitos del proyecto en un desarrollo que se lleva a cabo de manera lineal durante todo el proceso
        tr
          td Hay retroalimentaciones por cada iteración para hacer mejoras al producto durante el proceso de desarrollo
          td No hay retroalimentaciones durante el proceso de desarrollo
        tr
          td Realiza entregas del proyecto al terminar cada iteración
          td Realiza solo una entrega cuando finaliza el proyecto
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
