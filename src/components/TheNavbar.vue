<template>
  <div>
    <div class="container-logo">
      <img src="/img/dc-logo.png" alt="">
    </div>
    <div class="container-nav d-flex justify-content-center">
      <ul class="nav">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">characters</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Link</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Link</a>
        </li>
        <li class="nav-item">
          <a class="nav-link disabled">Disabled</a>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>

export default {
  name: "TheNavabar",
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>