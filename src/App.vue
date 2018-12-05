<template>
  <div id="app">
    <heading-navbar/>

    <home-page/>
    <footer-component/>
  </div>
</template>

<script>
import HomePage from "./components/HomePage.vue";
import HeadingNavbar from "./components/HeadingNavbar.vue";
import FooterComponent from "./components/FooterComponent.vue"
export default {
  name: "app",
  components: {
    HeadingNavbar,
    HomePage,
    FooterComponent
  }
};
</script>

<style>
@import "../node_modules/bulma/css/bulma.css";
body {
  background: #d6d6d6;
}

div#app {
  max-width: 1440px;
  margin: auto;
  background-color: #f2f2f2;
}
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  background-color: #ffffff;
}

</style>
