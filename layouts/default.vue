<template>
  <v-app>
    <AppMainHeader />
    <v-main
      class="blue-grey darken-4"
    >
      <v-container class="mx-auto">
        <v-row>
          <v-col>
            <h2 class="body__subtitle"> Hi, There 👋 </h2>
            <h1 class="body__title"> SIMON <br> NOZAKI </h1>
            <font-awesome-icon icon="fa-brands fa-twitter" />
          </v-col>
          <v-col>
            <Nuxt />
          </v-col>
        </v-row>
      </v-container>
    </v-main>
  </v-app>
</template>
