<template>
  <header id="header">
    <div class="main-logo">
      <img src="../assets/img/dc-logo.png" alt="DC Logo" />
    </div>
    <nav class="header-nav">
      <ul>
        <li>Characters</li>
        <li>Comics</li>
        <li>Movies</li>
        <li>Tv</li>
        <li>Games</li>
        <li>Collectable</li>
        <li>Video</li>
        <li>Fans</li>
        <li>News</li>
        <li>Shop</li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
  name: "Header",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss"></style>
