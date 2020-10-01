<template>
  <div class="column">
    <div class="card">
      <header class="card-header">
        <p class="card-header-title has-text-grey">
          {{ titulo }}
        </p>
      </header>
      <div class="card-content">
        <p class="content has-text-grey">
          {{ texto }}
        </p>
      </div>
      <footer class="card-footer">
        <div class="card-footer-item">
          <span>
            <p>Postado por: {{ autor }}</p>
          </span>
        </div>
      </footer>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    titulo: {
      type: String,
      required: true
    },
    autor: {
      type: String,
      required: true
    },
    texto: {
      type: String,
      required: true
    }
  }
}
</script>
