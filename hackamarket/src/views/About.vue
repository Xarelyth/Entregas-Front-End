<template>
  <div>
    <vue-headful title="About" />
    <menucustom></menucustom>
    <div class="about">
      <h1>Hello! This was a HACK A BOSS project for the Vue.js module</h1>
      <p>
        If you want to check out my Linkedin profile and learn more about me,
        click
        <a href="https://es.linkedin.com/in/brais-mont%C3%A1ns-bouza-75a412116"
          >here.</a
        >
      </p>
      <p>
        This website was made possible by the following node libraries:
        <br />
        <br />
        <a href="https://www.npmjs.com/package/axios">AXIOS</a>
        <br />
        <br />
        <a href="https://expressjs.com/">EXPRESS</a>
        <br />
        <br />
        <a href="https://www.npmjs.com/package/nodemon">NODEMON</a>
        <br />
        <br />
        <a href="https://jwt.io/">JWT TOKENS</a>
        <br />
        <br />
        <a href="https://expressjs.com/en/resources/middleware/cors.html"
          >CORS</a
        >
        <br />
        <br />
        <a href="http://expressjs.com/en/resources/middleware/body-parser.html"
          >BODY-PARSER</a
        >
        <br />
        <br />
        <a href="https://www.npmjs.com/package/mysql">MYSQL</a>
        <br />
        <br />
        <a href="https://sweetalert2.github.io/">SWEET ALERT 2</a>
        <br />
        <br />
        <a href="https://www.npmjs.com/package/vue-headful">VUE HEADFUL</a>
      </p>
    </div>
  </div>
</template>

<script>
import menucustom from "@/components/MenuCustom.vue";
import footercustom from "@/components/FooterCustom.vue";

export default {
  name: "About",
  components: { menucustom, footercustom },
};
</script>

<style scoped>
a {
  font-weight: bold;
  color: #cf4d6f;
}
.about {
  margin: 7rem;
}
</style>
