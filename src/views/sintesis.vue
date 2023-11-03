<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    p Los mecanismos de participación social y corresponsabilidad con la seguridad sanitaria orientan sobre aspectos relacionados con la política integral de salud ambiental, la cual tiene como ejes temáticos el agua y el saneamiento básico, aire y salud, sustancias químicas y residuos peligrosos, y cambio climático. Sin embargo, es necesario dar piso conceptual en relación con la normatividad que rige los derechos y deberes de todos los actores involucrados y las diferentes acciones y escenarios que son posibles de trabajar y ofrecer resultados.
    p.mb-5 En el siguiente gráfico, podrá reconocer una ruta resumida de los aspectos que involucran la temática tratada:

    .row.justify-content-center
      .col-lg-10.mb-5
        figure
          img(src="@/assets/curso/temas/sintesis.svg", alt="alt")
      .col-auto
        a.anexo.mb-4(:href="obtenerLink('/downloads/sintesis.pdf')" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-pdf.svg")
          .anexo__texto
            p Anexo. Síntesis

</template>

<script>
export default {
  name: 'Sintesis',
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
