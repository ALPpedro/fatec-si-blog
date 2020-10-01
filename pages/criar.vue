<template>
<section class="section">
  <div class="rows is-mobile">
    <form @submit.prevent="postarBlog">
          <div class="card-content">
        <input ref="titulo" v-model="titulo" placeholder="Titulo">
      </div>
      
        <div class="card-content">
        <input ref="autor" v-model="autor" placeholder="Autor">
      </div>
        <div class="card-content">
        <textarea ref="texto" v-model="texto" placeholder="Escreva aqui o texto que deseja postar." cols="30" rows="10"></textarea>
      </div>
        <div class="card-content">

          <button >Enviar</button>
      
      </div>
    </form>

    <p vif="erro" class="error">{{ erro }}</p>
  </div>
  </section>
</template>

<script>
export default {
  name: "criar",
  data() {
    return {
      titulo: "",
      autor: "",
      texto: "",
      erro:"",
    };
  },
  methods: {
    postarBlog() {
      this.erro = "";

      if (!this.titulo) {
        this.$refs.titulo.focus();
        this.erro = "Titulo não informado";
        return false;
      }

      else if(!this.autor){
      this.$refs.autor.focus();
      this.erro ="Autor não informado";
      return false;
      }
     else if(!this.texto){
      this.$refs.texto.focus();
      this.erro ="Informe um texto para continuar";
      return false;
      }
      else{this.erro ="texto enviado"}
    
          
    }
  }
};
</script>

