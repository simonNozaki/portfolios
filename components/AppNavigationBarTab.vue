<template>
  <v-tab
    nuxt
    link
    :to="to"
    class="navigation_link-text"
    active-class="navigation_link-text__active"
  >
    {{ text }}
  </v-tab>
</template>

<script>
export default {
  props: {
    text: String,
    to: String
  }
}
</script>
