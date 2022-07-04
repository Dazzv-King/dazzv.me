<template>
  <div>
    <Home></Home>
    <Contact></Contact>
  </div>
</template>

<script>
import Contact from "./components/d-contact.vue";
import Home from "./components/d-home.vue"

export default {
  name: "App",
  components: { 
    Contact,
    Home
  }
};
</script>

<style lang="scss">
</style>