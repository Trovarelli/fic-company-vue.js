<template>
    <div>
        <v-container d-flex fluid class="banner-grid">
          <v-row >
            <v-col id="anuncio" dense>
                Nós prometemos a <br>
                <b>melhor solução</b> <br>
                para seu negócio! <br>
                <a href="#servicos" class="btnScroll">Nossos serviços</a>
            </v-col>
            <v-col class="banner-animation">
              <img src="~/static/img/balao.png" id="balao">
              <img src="~/static/img/balao2.png" id="balao2">
              <img src="~/static/img/balao3.png" id="balao3">
              <img src="~/static/img/nuvem1.png" id="nuvem1">
              <img src="~/static/img/nuvem2.png" id="nuvem2">
              <img src="~/static/img/nuvem3.png" id="nuvem3">
            </v-col>
          </v-row>
        </v-container>
    </div>
</template>

<script>
export default {
    name: 'Banner',
    setup() {

    },
}
</script>

