<template>
  <section class="section">
    <div class="rows is-mobile">
      <card
        titulo="Lorem ipsum"
        texto="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris elementum, mi ac eleifend convallis, lacus dui facilisis magna, ac volutpat est dolor quis ante. Ut mattis dolor nec lacinia elementum. Quisque blandit ex eu ipsum aliquet, vitae fermentum nunc ullamcorper. Aenean lacinia mauris ex, tincidunt finibus enim fringilla viverra. Integer dui ipsum, pellentesque eget tempus a, suscipit nec mauris. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Cras tempor lectus in velit tincidunt tristique nec sed ligula. Aliquam vehicula lorem non justo volutpat condimentum. Duis laoreet semper tortor, eget congue mauris pulvinar a. Ut iaculis dui est, eu scelerisque arcu auctor ac.
Donec condimentum elit at dignissim efficitur. Suspendisse semper orci eget eros lobortis gravida. Ut ut ipsum id tellus congue vestibulum. Curabitur ullamcorper et lacus ac imperdiet. Curabitur consectetur vulputate enim in pellentesque. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per incepto."   autor="Paulo"
      >
      </card>
      <card
        title="Vue js"
        texto="Por conseguinte, a percepção das dificuldades afeta positivamente a correta previsão do levantamento das variáveis envolvidas. Percebemos, cada vez mais, que o fenômeno da Internet deve passar por modificações independentemente das novas proposições. É claro que a consulta aos diversos militantes obstaculiza a apreciação da importância do processo de comunicação como um todo. Percebemos, cada vez mais, que a consulta aos diversos militantes promove a alavancagem do impacto na agilidade decisória."
        autor="Pedro"
      >
      </card>
    </div>
  </section>
</template>

<script>
import Card from '~/components/Card'
export default {
  name: 'HomePage',

  components: {
    Card
  }
}
</script>
