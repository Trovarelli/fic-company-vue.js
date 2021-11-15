<template>
<div id="div-main">
  <v-spacer></v-spacer>
  <Banner />
  <div>
    <v-container class="servicos">
			<v-row>
				<v-col  align-self="center" class="container-prod">
					<img src="~/static/img/game.svg" width="150" height="150" alt="A imagem apresenta pequenos bonecos brincando, e se divertindo.">
					<h1>Gamificação</h1>
					<p> Criação de um jogo para sua empresa. </p>
				</v-col>

				<v-col  align-self="center" class="container-prod">
					<img src="~/static/img/analise.svg" width="150" height="150" alt="A imagem apresenta desenho de funcionarios na elaboração de um gráfico.">
					<h1>Analise</h1>
					<p> Analise e acompanhamento da sua empresa. </p>
				</v-col>

				<v-col  align-self="center" class="container-prod">
					<img src="~/static/img/website.svg" width="150" height="150" alt="A imagem mostra desenho de um funcionario desenvolvendo um website.">
					<h1>Websites</h1>
					<p> Criação de um site para sua empresa. </p>
				</v-col>
			</v-row>
			<v-spacer></v-spacer>
      <a class="verMais">Ver mais serviços</a>
			<a class="btnScroll" @click="scrollToBottom">Sobre nós</a>
      </v-container>
		  <v-container>
			<div class="containerSobre">
				<div class="msgSobre">
					<h1 id="sobreNos"> Sobre Nós: </h1>
					Somos uma empresa jovem, comprometida com a <br>
					excelência, qualidade e serviço. Somos movidos pela crença <br>
					de que grandes equipes podem ter sucesso e <br>
					somos apaixonados por construir grandes marcas.
				</div>
				<img src="~/static/img/sobre.svg" height="350" width="350" alt="Imagem mostra desenho de funcionarios montando as filosofias da empresa.">
			</div>
      <div class="servicos2">
        <a class="verMais">Ver mais serviços</a>
        <a class="btnScroll" @click="scrollToBottom2">Sobre nós</a>
      </div>
		</v-container>
    <ContatoForm />
    </div>
</div>
</template>

<script>
export default {
  setup() {

  },
  methods: {
  scrollToBottom() {
    window.scrollTo(0, 1300);
    },
    scrollToBottom2() {
    window.scrollTo(0, 1900);
    }
  }
}
</script>

