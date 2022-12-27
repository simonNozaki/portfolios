<template>
  <v-app>
    <AppMainHeader />
    <v-main
      class="blue-grey darken-4"
    >
      <v-container
      >
        <v-row>
          <v-col>
            <v-card
              flat
              dark
              class="blue-grey darken-4"
            >
              <v-card-subtitle class="text-h2 body__text"> Hi There 👋 </v-card-subtitle>
              <v-card-title class="text-h1 body__h1"> SIMON <br> NOZAKI </v-card-title>
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
