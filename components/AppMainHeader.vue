<template>
  <v-app-bar
    app
    flat
    class="amber darken-1"
  >
    <v-tabs right>
      <v-tabs-slider color="deep-purple darken-4"></v-tabs-slider>
      <v-tab
        to="/"
        class="navigation-bar__link body__text"
      >
        <v-icon> mdi-home </v-icon>
      </v-tab>
      <v-tab
        to="/about"
        class="navigation-bar__link body__text"
      >
        About
      </v-tab>
    </v-tabs>
  </v-app-bar>
</template>

<style scoped>
.navigation-bar__link {
  color: #263238;
  text-decoration: none;
}
</style>
