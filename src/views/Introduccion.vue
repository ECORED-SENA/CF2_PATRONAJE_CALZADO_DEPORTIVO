<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción

    .row.align-items-center.mb-5
      .col-xl-auto 
        figure.d-none.d-xl-block(data-aos="fade-right")
          img(src='@/assets/curso/intro/img1.svg', alt='' style="max-width: 100px").m-auto
      .col-xl
        p.mb-0 El desarrollo del calzado deportivo requiere una sólida comprensión técnica de los elementos que lo componen y de los procesos que permiten su correcta fabricación. Uno de los aspectos más importantes en esta labor es el conocimiento de los sistemas de medidas, los cuales garantizan un ajuste adecuado al pie del usuario, tanto en longitud como en volumen. Comprender las equivalencias entre tallas, así como las medidas de ancho o perímetro, resulta fundamental para alcanzar un diseño funcional y anatómicamente correcto.
    
    .fondo___img.espacio___movil_1
      .px-5
        .row.align-items-center
          .col-xl
            .row.align-items-center.mb-4
              .col-xl-auto
                figure.d-none.d-xl-block(data-aos="fade-right")
                  img(src='@/assets/curso/intro/img2.png', alt='' style="max-width: 400px").m-auto
              .col-xl
                p.mb-0.estilo___caja_1 En este proceso, la horma desempeña un papel central al funcionar como el molde tridimensional sobre el cual se construye el zapato. Estudiar sus partes, dimensiones y clasificaciones permite adaptar la forma del calzado a diferentes tipos de pie, usuarios y usos específicos. La relación entre la estructura del pie, el tipo de pisada y el diseño de la horma no solo mejora la comodidad y el rendimiento, sino que también previene lesiones y favorece la salud postural del usuario.
            p.mb-0.estilo___caja_2 Adicionalmente, el componente formativo incluye el aprendizaje del proceso de enmascarado, una técnica esencial para trasladar con precisión las formas de la horma a un plano bidimensional, lo que facilita el trazado de patrones. El uso adecuado de herramientas técnicas especializadas y el dominio de esta metodología permite al aprendiz desarrollar moldes que respondan a criterios de calidad, ergonomía y funcionalidad en el diseño del calzado deportivo.
          .col-xl-auto(data-aos="fade-left")
            figure.d-none.d-xl-block
              img(src='@/assets/curso/intro/img3.png', alt='' style="max-width: 300px").m-auto

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
