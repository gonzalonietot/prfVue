<template>
  <div class="container">
    <header-component />
    <main-component />
    <footer-component />
  </div>
</template>

<script>
import main from "@/components/Main";
import header from "@/components/Header";
import footer from "@/components/Footer";
export default {
  name: "Container",
  components: {
    'header-component': header,
    'main-component': main,
    'footer-component': footer
  }
}
</script>

<style scoped lang="scss" src="../styles/Container.scss"></style>