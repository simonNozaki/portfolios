<template>
  <v-btn
    :href="to"
    text
    small
    outlined
    style="text-transform: none;"
  >
    {{ text }}
  </v-btn>
</template>

<script>
export default {
  props: {
    to: String,
    text: String
  }
}
</script>
