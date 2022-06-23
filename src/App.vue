<template>
  <div id="App">
    <TheNavbar></TheNavbar>


    <main>
      <div class="jumbo-container">

      </div>
      <div class="container-fumetti py-5">
        <ProductsList></ProductsList>
        <div class="load-more-container d-flex justify-content-center ">
          <div class="btn-load-more text-white fw-bold py-2 px-5 mb-2 ">LOAD MORE</div>
        </div>
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

.jumbo-container {
  background-image: url("/public/img/jumbotron.jpg");
  background-size: cover;
  background-position: top;
  background-repeat: no-repeat;
  height: 350px;
}

.container-fumetti {
  background-color: #1C1C1C;
  padding-left: 150px;
  padding-right: 150px;

}

.btn-load-more{
  background-color: #0282F9;
}
</style>
