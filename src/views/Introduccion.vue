<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    
    p(data-aos="fade-right").mb-5 Los mecanismos de participación social son medios que posibilitan materializar el derecho desde el ejercicio democrático, desde el ejercicio de deberes y derechos en pro de garantizar la salud a nivel personal y comunitario. Le invitamos a ver el siguiente video, que ofrece de manera general las temáticas que aborda este componente formativo en torno a la participación social:

    figure
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/70C8VZOH8WM?si=AF5VJJ9idM2GxB7D" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen)




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
