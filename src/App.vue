<template>
  <nav>
    <Header />
  </nav>
  <div class="page-content">
    <router-view />
  </div>
  <Footer />
</template>
<script>
import Header from "@/components/Header.vue";
import Footer from "@/components/Footer.vue";
export default {
  name: "AppView",
  components: {
    Header,
    Footer,
  },
};
</script>
<style lang="scss">
body {
  /* background: #191919;
  color: #fff; */
  // height: 3000px;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

/* nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
} */
</style>
