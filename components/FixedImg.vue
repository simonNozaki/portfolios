<template>
  <img :src="src" :alt="alt" height="20" width="20" />
</template>

<script>
export default {
  props: {
    src: {
      type: String,
      default: 'NOT FOUND',
    },
    alt: {
      type: String,
      default: 'NOT FOUND',
    },
  },
}
</script>
