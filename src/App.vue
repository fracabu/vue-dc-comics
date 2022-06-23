<template>
  <div id="App">
    <TheNavbar></TheNavbar>
    <TheMain></TheMain>
    <ListaFumetti></ListaFumetti>
    <FumettiCard></FumettiCard>
    <TheBannerBlue></TheBannerBlue>
    <TheFooter></TheFooter>
    <TheBannerSignUp></TheBannerSignUp>
    
  </div>
</template>


<script>
import TheNavbar from "./components/TheNavbar.vue"
import TheMain from "./components/TheMain.vue"
import TheBannerBlue from "./components/TheBannerBlue.vue"
import TheFooter from "./components/TheFooter.vue"
import TheBannerSignUp from "./components/TheBannerSignUp.vue"
import ListaFumetti from "./components/ListaFumetti.vue"
import FumettiCard from "./components/FumettiCard.vue"



export default {
  name: "App",
  components: { TheNavbar, TheMain, TheBannerBlue, TheFooter, TheBannerSignUp, ListaFumetti, FumettiCard },
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
