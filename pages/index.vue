<template>
  <v-row justify="center" align="center">
    <v-col cols="12" sm="8" md="6">
      <v-card>
        <v-card-title class="headline">
          Welcome to this example app made with Vuetify + Nuxt.js
        </v-card-title>

        <v-card class="logo py-4 d-flex justify-center">
          <NuxtLogo />
          <VuetifyLogo />
        </v-card>

        <v-card-text>
          <p>
            Vuetify is a progressive Javascript library that implements Google's
            Material Design concept, in a component framework and specifically
            designed for Vue.js
          </p>
          <p>
            The
            <a
              href="https://vuetifyjs.com"
              target="_blank"
              rel="noopener noreferrer"
              >Vuetify</a
            >
            thats used here is v2.6.10
          </p>
          <p>
            I'm using
            <a
              href="https://nuxtjs.org/"
              target="_blank"
              rel="noopener noreferrer"
              title="chat"
            >
              Nuxt.js</a
            >
            here, at version 2.15.8
          </p>
          <p>
            The actual
            <a
              href="https://github.com/vuetifyjs/vuetify/issues"
              target="_blank"
              rel="noopener noreferrer"
              title="contribute"
            >
              Vue</a
            >
            library is at v2.7.10
          </p>
          <div class="text-xs-right">
            <em>crenaz</em>
          </div>
          <hr class="my-3" />
        </v-card-text>
        <v-card-actions>
          <v-spacer />
          <v-btn color="primary" nuxt to="/inspire">
            Continue to next page</v-btn
          >
        </v-card-actions>
      </v-card>
    </v-col>
  </v-row>
</template>

<script>
export default {
  name: 'IndexPage',
}
</script>
