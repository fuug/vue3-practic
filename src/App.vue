<template>
  <nav>
    <VLink :link="'/'">Home</VLink>
    <VLink :link="'/about'">About</VLink>
  </nav>
  <router-view/>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

</style>
<script>
import VLink from "@/components/VComponents/VLink";
export default {
  components: {VLink}
}
</script>