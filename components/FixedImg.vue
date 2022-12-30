<template>
  <img
    :src="src"
    :alt="alt"
    height="20"
    width="20"
  />
</template>

<script>
export default {
  props: {
    src: String,
    alt: String
  }
}
</script>
