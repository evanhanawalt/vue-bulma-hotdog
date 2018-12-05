<template>
  <div>
    <figure class="image is-3by1">
      <a href="#">
        <img src="../assets/banner.jpg">
      </a>
    </figure>
    <nav
      class="navbar center-nav is-flex-tablet-only justify-content-center"
      role="navigation"
      aria-label="main navigation"
    >
      <a href="#" class="navbar-item">Home</a>
      <a href="#" class="navbar-item">Documentation</a>
      <a href="#" class="navbar-item">Home</a>
      <a href="#" class="navbar-item">Documentation</a>
    </nav>
  </div>
</template>

<script>
export default {
  name: "HeadingNavbar",
  props: {
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>


a.navbar-item {
  justify-content: center;
  display: flex;
  flex-direction: column;
}

.center-nav {
  text-align: center;
  justify-content: center;
  vertical-align: middle;
  -webkit-box-shadow: 0px 0px 8px 0px rgba(0, 0, 0, 0.75);
  -moz-box-shadow: 0px 0px 8px 0px rgba(0, 0, 0, 0.75);
  box-shadow: 0px 0px 8px 0px rgba(0, 0, 0, 0.75);
}

.navbar {
  justify-content: center;
  align-content: center;
}
</style>
