<template>
  <v-app-bar
    app
    dense
    class="teal accent-3"
  >
    <v-tabs
      right
      slider-color="blue-grey darken-4"
    >
      <v-tab>
        <nuxt-link
          to="/" class="navigation__link-text"
        > <v-icon> mdi-home </v-icon> </nuxt-link>
      </v-tab>
      <v-tab>
        <nuxt-link
          to="/works"
          class="text-decoration-none navigation__link-text"
        > works </nuxt-link>
      </v-tab>
    </v-tabs>
  </v-app-bar>
</template>