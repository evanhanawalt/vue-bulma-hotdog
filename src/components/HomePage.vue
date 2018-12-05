<template>
  <div>
    <section class="hero is-light">
      <div class="hero-body banner-container">
        <figure class="image is-64x64">
          <img src="../assets/icon.svg">
        </figure><br>
        <h1 class="title">Dirty Dogs Serves all beef, vegan, and vegetarian hotdogs.</h1>
        <a class="button is-info">More Dogs 'n Make Em Hot</a>
      </div>
    </section>





    <div class="columns is-gapless is-multiline">
      <div class="column is-half fill">
        <img src="../assets/beef.jpg">
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
        <img src="../assets/vegan.jpg">
      </div>

      <div class="column is-half is-hidden-tablet description-container">
        <h1 class="title">&mdash; Vegan Hotdogs</h1>
        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Eligendi excepturi fugit laborum quia, explicabo voluptas magnam quo aspernatur quis fugiat.</p>
      </div>

      <div class="column is-half fill">
        <img src="../assets/vegetarian.jpg">
      </div>

      <div class="column is-half description-container">
        <h1 class="title">&mdash; Vegetarian Hotdogs</h1>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eligendi ipsum quam quos quis esse possimus recusandae unde distinctio enim obcaecati?</p>
      </div>
    </div>

  </div>
</template>

<script>
export default {
  name: "HomePage",
  props: {
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
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
