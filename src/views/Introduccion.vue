<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    p.mb-5(data-aos="fade-left") El éxito corporativo en el mundo económico es siempre el propósito común que busca cualquier organización. Sobre esta base, las compañías definen la razón de ser de su existencia, contextualizan sus propósitos y aspiraciones al tiempo que estructuran sobre estas, los objetivos y las metas a alcanzar en un período de tiempo determinado. Por lo anterior, se invita a ver el siguiente video que permitirá adentrarse en la temática a tratar.
    
    figure.mb-5(data-aos="zoom-in")
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/LY3rrDvyCWA?si=NPkQViP6lAU2KMod" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

    
</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
