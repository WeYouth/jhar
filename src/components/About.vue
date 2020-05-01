<template>
  <section class="hero">
    <div class="hero-head">
      <h1 class="title">من نحن؟</h1>
    </div>
    <div class="hero-body">
      <div class="container">
        <div class="columns">
          <div class="column">Video</div>
          <div class="column">
            <h1 class="about">جهار هي منصة إعلامية رقمية بمحتوى شبابي يعكس مشاغل المجتمع و يناقش قضاياه بطريقة مبتكرة</h1>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "About"
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.title {
  margin: 40px 0 0;
}

.about{
  font-size: 3rem;
  font-weight: 400;
  line-height: 1.125;
}

ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
