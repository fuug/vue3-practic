<template>
  <router-link :to="$props.link" class="link">
    <slot/>
  </router-link>
</template>

<script>
export default {
  name: "VLink",
  props: {
    link: String
  }
}
</script>

<style scoped>
.link {
  color: #000;
  margin-right: 10px;
  font-weight: 700;
  font-size: 18px;
}

.router-link-active {
  color: #324794;
}
</style>