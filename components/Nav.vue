<template>
  <v-app-bar class="px-8 elevation-5 rounded-b-xl sticky" elevate-on-scroll flat fixed color="white"  max-height="10vh">
      <v-toolbar-title>
        <img src="~/static/img/logo.png" width="100" alt="j-team">
      </v-toolbar-title>
      <v-spacer></v-spacer>
      <div class="d-flex aligin-center">
        <div class="px-3 ml-3 py-1 rounded">
          <small>
            <nuxt-link to="/" class="verMais"><h3>Home</h3></nuxt-link>
          </small>
        </div>
        <div class="px-3 ml-3 py-1 rounded">
          <small>
            <nuxt-link to="/servicos" class="verMais"><h3>Serviços</h3></nuxt-link>
          </small>
        </div>
        <div class="px-3 ml-3 py-1 rounded">
          <small>
            <nuxt-link to="#" class="verMais"><h3>Sobre</h3></nuxt-link>
          </small>
        </div>
        <div class="px-3 ml-3 py-1 rounded">
          <small>
            <nuxt-link to="#" class="verMais"><h3>Contato</h3></nuxt-link>
          </small>
        </div>
      </div>
    </v-app-bar>
</template>
