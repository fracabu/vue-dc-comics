<template>
  <div>

    <div class="container-nav d-flex justify-content-start mx-5">
      <div class="box-logo py-3"><img src="/img/dc-logo.png" alt="" class="logo"></div>
      <ul class="nav align-items-center text-uppercase fw-bold">
        <li class="nav-item" v-for="(link, i) in navLinks" :key="i">
          <a class="nav-link" :href="link.href">{{ link.name }}</a>
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

.box-logo {
  flex-grow: 1;
  margin-left: 200px;

}

.logo {
  width: 80px;
}
</style>