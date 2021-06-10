<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/title.gif" />
    <h1>What is <router-link to="/about">NYC</router-link>?</h1>
  </div>
  <!-- <Header /> -->
</template>

<script>
// @ is an alias to /src
// import Header from "@/components/Header.vue";

// export default {
//   name: "Home",
//   components: {
//     Header,
//   },
// };
</script>

<style>
body {
  background-color: #e4ccff;
}
.container {
  background-color: white;
  padding: 100px 0;
}
img {
  width: 70%;
  height: auto;
  padding-bottom: 30px;
}

h1 {
  font-size: 30px;
}
h1 a {
  font-size: 35px;
}

a {
  font-weight: bold;
  font-size: 20px;
  color: black;
}

a:hover {
  color: #b48bff;
}

.btn {
  width: 25%;
  height: auto;
}
</style>
