<template>
    <div>
        <div class="container-signup d-flex align-items-center">
            <div class="box-signup py-2">
                <span class="text-white text-uppercase fw-bold px-2">sign up-now!</span>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "TheBannerSignUp",
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

.container-signup {
    height: 120px;
    background-color: #303030;
}

.box-signup {
    border: 2px solid #0282F9;
    margin-left: 120px;
    
}
</style>