<template>
  <div>

    <footer class="footer-container">
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
  name: "FooterComponent",
  props: {
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>


.footer-container {
  padding: 1rem;
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
}


</style>
