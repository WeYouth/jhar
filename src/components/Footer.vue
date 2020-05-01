<template>
  <footer class="footer">
  <div class="content has-text-centered">
    <p>
      <strong>J'har</strong> is a brand owned by WeYouth Organization. The source code of this website is under
      <a href="http://opensource.org/licenses/mit-license.php">MIT</a> license. The website content
      is licensed <a href="http://creativecommons.org/licenses/by-nc-sa/4.0/">CC BY NC SA 4.0</a>.
    </p>
  </div>
</footer>
</template>

<script>
export default {
  name: "Footer"
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
