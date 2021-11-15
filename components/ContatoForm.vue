<template>
  <v-container>
    <div class="contato">
			<div class="containerContato">
				<img src="~/static/img/contato.svg" class="img-contato" alt="A imagem apresenta a troca de informações entre o cliente e a empresa.">
				<v-form class="form-contato">
					<h4> Nos contate: </h4>
					<v-text-field color="teal lighten-2" filled rounded type="text" name="" placeholder="Fulano da Silva"></v-text-field>
					<v-text-field color="teal lighten-2" filled rounded type="email" name="" placeholder="Fulano@email.com"></v-text-field>
					<v-text-field color="teal lighten-2" filled rounded type="text" name="" placeholder="Assunto:"></v-text-field>
					<v-textarea color="teal lighten-2"  filled cols="50" rows="5" placeholder="Mensagem:"></v-textarea>
					<v-btn type="submit" color="teal lighten-1" rounded depressed>Enviar</v-btn>
					<v-btn type="reset" color="red darken-1" rounded  depressed>Cancelar</v-btn>
				</v-form>
			</div>
      <a @click="scrollToTop" class="verMais">Voltar ao inicio</a>
		</div>
  </v-container>
</template>

<script>
export default {
  setup() {

  },
  methods: {
    scrollToTop() {
      window.scrollTo(0,0);
    },
  }
}
</script>

