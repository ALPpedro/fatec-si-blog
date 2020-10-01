<template>
  <section class="section">
    <div class="rows is-mobile">
      <n-link to="/mostrar">
      <card
        titulo="Fatec em crise"
        texto="Clique aqui para ler sobre."
        autor="Paulo"
      >
      </card>
      </n-link>
      <n-link to="/mostrar">
      <card
        titulo="Vue js"
        texto="Clique aqui para ler sobre."
        autor="Pedro"
      >
      </card>
      </n-link>
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
