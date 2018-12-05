<template>
  <div id="app">
    <figure class="image is-3by1">
      <a href="#">
        <img src="./assets/banner.jpg">
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

    <section class="hero is-light">
      <div class="hero-body banner-container">
        <figure class="image is-64x64">
          <img src="./assets/icon.svg">
        </figure><br>
        <h1 class="title">Dirty Dogs Serves all beef, vegan, and vegetarian hotdogs.</h1>
        <a class="button is-info">More Dogs 'n Make Em Hot</a>
      </div>
    </section>

    <div class="columns is-gapless is-multiline">
      <div class="column is-half fill">
        <img src="./assets/beef.jpg">
      </div>

      <div class="column is-half description-container">
        <div class>
          <h1 class="title">&mdash; Gormet All Beef Hotdogs</h1>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dignissimos repellendus fuga dicta unde sed libero omnis excepturi mollitia ut quas.</p>
        </div>
      </div>

      <div class="column is-half is-hidden-mobile description-container">
        <div class="content">
          <h1 class="title">&mdash; Vegan Hotdogs</h1>
          <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Modi explicabo animi laborum. Quia reiciendis ducimus adipisci inventore impedit sequi nihil.</p>
        </div>
      </div>

      <div class="column is-half fill">
        <img src="./assets/vegan.jpg">
      </div>

      <div class="column is-half is-hidden-tablet description-container">
        <h1 class="title">&mdash; Vegan Hotdogs</h1>
        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Eligendi excepturi fugit laborum quia, explicabo voluptas magnam quo aspernatur quis fugiat.</p>
      </div>

      <div class="column is-half fill">
        <img src="./assets/vegetarian.jpg">
      </div>

      <div class="column is-half description-container">
        <h1 class="title">&mdash; Vegetarian Hotdogs</h1>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eligendi ipsum quam quos quis esse possimus recusandae unde distinctio enim obcaecati?</p>
      </div>
    </div>

    <footer class="footer-padding">
      <div>© 2016 Dirty Dogs All Rights Reserved</div>
      <div>
        123 Marconi Blvd. Columbus Ohio, 43215 | 123.456.7890 |
        <a
          href="#"
          class="has-text-grey"
        >Contact Us</a>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  name: "app",
  components: {}
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

a.navbar-item {
  justify-content: center;
  display: flex;
  flex-direction: column;
}

.columns {
  margin-bottom: 0 !important;
  background-color: #ffffff;
}
div.column {
  text-align: center;
  background-color: #ffffff;
}
.fill img {
  flex-shrink: 0;
  min-width: 100%;
  min-height: 100%;
}
.footer-padding {
  padding: 1rem;
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
}

div.description-container > * {
  text-align: left;
  margin: 10%;
}

.banner-container {
  text-align: center;
}

.banner-container > * {
  margin: auto;
}
a.button.is-info {
  background-color: #20546e;
}
</style>
