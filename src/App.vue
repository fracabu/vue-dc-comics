<template>
  <div id="App">
    <TheNavbar></TheNavbar>

    <main>
      <div class="container-fumetti bg-danger">
        contenuto della pagina
        <ProductsList></ProductsList>
      </div>
    </main>

    <TheBannerBlue></TheBannerBlue>
    <TheFooter></TheFooter>
    <TheBannerSignUp></TheBannerSignUp>

  </div>
</template>


<script>
import TheNavbar from "./components/TheNavbar.vue"
import TheBannerBlue from "./components/TheBannerBlue.vue"
import TheFooter from "./components/TheFooter.vue"
import TheBannerSignUp from "./components/TheBannerSignUp.vue"
import ProductsList from "./components/ProductsList.vue"




export default {
  name: "App",
  components: { TheNavbar, TheBannerBlue, TheFooter, TheBannerSignUp, ProductsList },
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
