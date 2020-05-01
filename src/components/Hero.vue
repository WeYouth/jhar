<template>
  <section class="hero is-primary">
    <div class="hero-body">
      <div class="container">
        <img src="../assets/jhar-white.png" class="brand" alt="Logo" />
        <h1 class="title">.عبر، أثّر، غيّر</h1>

        <b-button type="is-danger" icon-right="delete" href="#follow-us">
          <strong>تابعونا</strong>
        </b-button>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Hero"
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import "@/assets/style.scss";

h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}

.brand {
  max-height: 10em;
}
</style>
