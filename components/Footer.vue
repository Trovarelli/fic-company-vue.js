<template>
   <v-footer color='rgb(21, 24, 39)' rounded="t-xl">
			<img src="img/logow.png" id="img-footer">

			<div id="mapaSite">
				<p style="">Páginas</p>
					<router-link to="#" class="site"><h3>Home</h3></router-link>
					<router-link to="#" class="site"><h3>Serviços</h3></router-link>
					<router-link to="#" class="site"><h3>Sobre</h3></router-link>
					<router-link to="#" class="site"><h3>Contato</h3></router-link>
			</div>

			<div id="mapaSite">
				<p style="">Ajuda</p>
					<router-link to="#" class="site"><h3>Acessibilidade</h3></router-link>
          <v-spacer></v-spacer>
					<router-link to="#" class="site"><h3>Termos e Condições</h3></router-link>
          <v-spacer></v-spacer>
					<router-link to="#" class="site"><h3>Termos de Uso</h3></router-link>
          <v-spacer></v-spacer>
					<router-link to="#" class="site"><h3>Termos de Privacidade</h3></router-link>
			</div>

			<v-card flat tile color="rgb(21, 24, 39)" class="white--text text-center">
				<p>Siga nossas redes sociais</p>
					<v-btn v-for="icon in icons" :key="icon" class="mx-4 white--text" icon>
          <v-icon size="24px">
            {{ icon }}
          </v-icon>
        </v-btn>
			</v-card>

			<div id="newsletters">
				<p>Inscreva-se nas nossas newsletters!</p>
					<input class="inputFt" type="email" name="" placeholder="fulano@email.com">
					<button class="btnSubmitFt" type="submit" >Enviar</button>
			</div>
		</v-footer>
</template>

<script>
  export default {
      data: () => ({
        icons: [
          'mdi-facebook',
          'mdi-twitter',
          'mdi-linkedin',
          'mdi-instagram',
        ],
      }),
    }
</script>
