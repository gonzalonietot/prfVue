<template>
  <header class="header">
    <nav class="header__nav">
      <p class="header__logo">{{ name }}</p>
      <div class="header__links">
        <ol>
          <li>About me</li>
          <li>Proyects</li>
          <li>Work</li>
          <li>Resume</li>
        </ol>
      </div>
    </nav>
  </header>
</template>

<script>
export default {
  name: "Header",
  data() {
    return {
      name: '< Gonzalo />'
    }
  }
}
</script>

<style scoped lang="scss" src="../styles/Header.scss">

</style>