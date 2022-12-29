<template>
  <v-app>
    <!-- <AppMainHeader /> -->
    <v-main
      class="blue-grey darken-4"
    >
      <v-container class="mx-auto">
        <v-row>
          <v-col>
            <h2 class="body__subtitle"> Hi, There 👋 </h2>
            <h1 class="body__title"> SIMON <br> NOZAKI </h1>
            <v-card
              flat
              dark
              class="blue-grey darken-4"
            >
              <a href="https://twitter.com/catch_all_balls" class="ma-2"> <v-icon> mdi-twitter </v-icon> </a>
              <a href="https://github.com/simonnozaki" class="ma-2"> <v-icon> mdi-github </v-icon> </a>
              <a href="https://qiita.com/s_9_i" class="ma-2">
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
