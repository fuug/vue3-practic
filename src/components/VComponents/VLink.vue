<template>
  <router-link :to="$props.link">
    <slot/>
  </router-link>
</template>

<script>
export default {
  name: "VLink",
  pops: {
    link: String
  }
}
</script>

<style scoped>

</style>