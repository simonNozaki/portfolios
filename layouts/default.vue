<template>
  <v-app>
    <AppNavigationBar />
    <v-main class="blue-grey darken-4">
      <v-container class="mx-auto">
        <v-row no-gutters>
          <v-col sm="6">
            <h2 class="body__subtitle">Hej,</h2>
            <h1 class="body__title">SIMON NOZAKI</h1>
            <v-card flat dark class="blue-grey darken-4">
              <a href="https://twitter.com/serum_vision" class="ma-2">
                <v-chip>
                  <v-icon> mdi-twitter </v-icon>
                </v-chip>
              </a>
              <a href="https://github.com/simonnozaki" class="ma-2">
                <v-chip>
                  <v-icon> mdi-github </v-icon>
                </v-chip>
              </a>
              <a href="https://qiita.com/s_9_i" class="ma-2 body__text">
                <v-chip color="green" text-color="white"> Qiita </v-chip>
              </a>
            </v-card>
          </v-col>
          <v-col>
            <Nuxt />
          </v-col>
        </v-row>
      </v-container>
    </v-main>
  </v-app>
</template>
