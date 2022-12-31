<template>
  <v-tab
    :to="to"
    class="navigation_link-text"
    style="text-transform: none;"
  >
    {{ text }}
  </v-tab>
</template>

<script>
export default {
  props: {
    text: {
      type: String,
      default: 'NOT FOUND',
    },
    to: {
      type: String,
      default: 'NOT FOUND',
    },
  },
}
</script>
