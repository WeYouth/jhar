<template>
  <section class="hero is-medium">
    <div class="hero-body">
      <div class="container">
        <h1 class="title">تابعونا وشاهدوا محتوانا على مختلف الوسائط الاجتماعية</h1>

        <div class="block">
            <b-icon
                icon="facebook"
                size="is-large"
                type="is-info">
            </b-icon>
            <b-icon
                icon="instagram"
                size="is-large"
                type="is-info">
            </b-icon>
            <b-icon
                icon="youtube"
                size="is-large"
                type="is-info">
            </b-icon>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Follow"
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
