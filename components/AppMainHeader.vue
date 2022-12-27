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
        class="navigation-bar__link"
      >
        Home
      </v-tab>
      <v-tab
        to="/about"
        class="navigation-bar__link"
      >
        About
      </v-tab>
      <v-tab>
        <a
          href="https://twitter.com/catch_all_balls"
          class="navigation-bar__link"
        >
          <v-icon> mdi-twitter </v-icon>
        </a>
      </v-tab>
      <v-tab>
        <a
          href="https://github.com/simonnozaki"
          class="navigation-bar__link"
        >
        <v-icon> mdi-github </v-icon>
        </a>
      </v-tab>
      <v-tab>          
        <a
          href="https://qiita.com/s_9_i"
          class="navigation-bar__link"
        > Qiita </a>
      </v-tab>
    </v-tabs>    
  </v-app-bar>
</template>
