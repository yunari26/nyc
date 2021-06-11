<template>
  <Header />
  <div class="container">
    <router-view />
  </div>
  <Footer />
</template>

<script>
import Footer from "@/components/Footer.vue";
import Header from "@/components/Header.vue";

export default {
  name: "App",
  components: {
    Header,
    Footer,
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Coming+Soon&family=Gaegu&family=Kiwi+Maru:wght@300&family=Walter+Turncoat&display=swap");

#app {
  /* font-family: Avenir, Helvetica, Arial, sans-serif; */
  /* font-family: "Coming Soon", cursive; */
  font-family: "Gaegu", "Kiwi Maru", cursive;

  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
  color: white;
}

a {
  font-weight: bold;
  font-size: 20px;
}

a:hover {
  color: #b48bff;
  text-decoration: none !important;
}
</style>
