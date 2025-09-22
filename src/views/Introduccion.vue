<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    .row.justify-content-center.align-items-center.mb-3
      .col-12.col-lg-9
        p.mb-lg-3.mb-4 En el universo digital actual, destacar entre millones de mensajes exige algo más que visibilidad: requiere conexión. Este componente formativo aborda la narrativa como herramienta para crear contenido significativo y emocionalmente efectivo. A través de seis módulos se exploran desde los elementos narrativos esenciales hasta el desarrollo técnico de piezas digitales. La formación combina teoría y práctica para construir relatos que inspiran, persuaden y permanecen. El <i>storytelling</i> aquí no es solo estructura: es puente comunicacional. Es la estrategia detrás del mensaje que conecta con la audiencia.
        .row.justify-content-center.align-items-center.mb-lg-3.mb-4
          .col-6.col-lg-3.mb-lg-0.mb-4.d-flex
            figure.w-100.d-flex.flex-column
              img(src='@/assets/curso/introduccion/img_2.png', class="img-fluid")
          .col-12.col-lg-9
            p.mb-0  El objetivo principal del componente es desarrollar la capacidad de diseñar contenidos con intención y sentido. Contar historias digitales implica comprender emociones, adaptar formatos y articular ideas en función de una narrativa clara. Se busca fortalecer habilidades que permitan al aprendiz planear, producir y evaluar piezas desde una mirada creativa y estratégica.
      .col-8.col-lg-3.d-flex
        figure.w-100.d-flex.flex-column
          img(src='@/assets/curso/introduccion/img_1.png', class="img-fluid").height-100
    figure
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/XtJsfNhoDWo?si=_RbBpMwU3qqWIfmR" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

      
</template>

<script>
export default {
  name: 'Introduccion',
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
