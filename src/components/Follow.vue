<template>
  <section class="hero is-medium">
    <div class="hero-body">
      <div class="container">
        <h1 class="title">تابعونا وشاهدوا محتوانا على مختلف المنصات الاجتماعية</h1>

        <div class="block">
          <ul>
            <li>
              <a href="https://www.facebook.com" target="blank">
                <b-icon icon="facebook" custom-size="fa-5x" type="is-info"></b-icon>
              </a>
            </li>
            <li>
              <a href="https://www.instagram.com" target="blank">
                <b-icon icon="instagram" custom-size="fa-5x" type="is-info"></b-icon>
              </a>
            </li>
            <li>
              <a href="https://www.youtube.com" target="blank">
                <b-icon icon="youtube" custom-size="fa-5x" type="is-info"></b-icon>
              </a>
            </li>
          </ul>
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

.title{
  font-size: 3rem;
  font-weight: 600;
  line-height: 1.125;
}

ul {
  list-style-type: none;
  padding: 0;
  margin-top: 5em;
}
li {
  display: inline-block;
  margin: 0 5em;
}

.brand {
  max-height: 10em;
}

@media screen and (max-width: 620px){
  li{
    margin: 0 3em ;
  }
}

@media screen and (max-width: 480px){
  .title{
  font-size: 2rem;
  font-weight: 600;
  line-height: 1.125;
}
  li{
    display: block;
    margin: 3em ;
  }
}
</style>
