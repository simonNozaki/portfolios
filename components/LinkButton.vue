<template>
  <v-btn :href="to" text small outlined style="text-transform: none">
    {{ text }}
  </v-btn>
</template>

<script>
export default {
  props: {
    to: {
      type: String,
      default: 'NOT FOUND',
    },
    text: {
      type: String,
      default: 'NOT FOUND',
    },
  },
}
</script>
