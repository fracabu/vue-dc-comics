<template>
  <div>
    <div class="container-logo">
      <img src="/img/dc-logo.png" alt="">
    </div>
    <div class="container-nav d-flex justify-content-center">
      <ul class="nav">
        <li class="nav-item" v-for="(link,i) in navLinks" :key="i">
          <a class="nav-link" :href="link.href">{{link.name}}</a>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>

export default {
  name: "TheNavabar",
  data() {
    return {
      navLinks: [
        {
          name: "Characters",
          href: "#",
        },
        {
          name: "Comics",
          href: "#",
        },
        {
          name: "Movies",
          href: "#",
        },
        {
          name: "TV",
          href: "#",
        },
        {
          name: "Games",
          href: "#",
        },
        {
          name: "Collectibles",
          href: "#",
        },
        {
          name: "Videos",
          href: "#",
        },
        {
          name: "Fans",
          href: "#",
        },
        {
          name: "New",
          href: "#",
        },
        {
          name: "Shop",
          href: "#",
        },
      ]

    }
  },
};
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