<template>
    <div>

        <footer class="img-bg">
            <div class="container">
                <div class="row">
                    <div class="col-2 text-white py-5">
                        <h5>DC COMICS</h5>
                        <ul class="list-unstyled">
                            <li v-for="link in dcComicsLinks" :key="link">
                                {{ link }}
                            </li>
                        </ul>
                        <h5>SHOP</h5>
                        <ul class="list-unstyled">
                            <li v-for="link in shopLinks" :key="link">
                                {{ link }}
                            </li>
                        </ul>
                    </div>
                    <div class="col-2 text-white py-5">
                        <h5>DC</h5>
                        <ul class="list-unstyled">
                            <li v-for="link in dcLinks" :key="link">
                                {{ link }}
                            </li>
                        </ul>
                    </div>
                    <div class="col-2 text-white py-5">
                        <h5>SITES</h5>
                        <ul class="list-unstyled">
                            <li v-for="link in sitesLinks" :key="link">
                                {{ link }}
                            </li>
                        </ul>
                    </div>
                    <div class="col-6">
                        <img src="/img/dc-logo-bg.png" alt="">
                    </div>
                </div>
            </div>
        </footer>

    </div>
</template>

<script>
export default {
    name: "TheFooter",
    data() {
        return {
            dcComicsLinks: [
                "Characters",
                "Comics",
                "Movies",
                "Tv",
                "Games",
                "Videos",
                "News",
            ],
            shopLinks: [
                "Characters",
                "Characters",
            ],

            dcLinks: [
                "Characters",
                "Characters",
                "Characters",
                "Characters",
                "Characters",
                "Characters",
                "Characters",
                "Characters",
                "Characters",
                "Characters",
                "Characters",
            ],

            sitesLinks: [
                "Characters",
                "Characters",
                "Characters",
                "Characters",
                "Characters",
            ]
        }

    }
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

.img-bg {
    background-image: url("/public/img/footer-bg.jpg");
    background-size: contain;
    background-position: center;
    background-repeat: no-repeat;

}
</style>