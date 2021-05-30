<template>
  <div><div class="content">
  <canvas class="snow" id="snow"></canvas>
  <div class="main-text">
    <h1>Aw jeez.<br/>That page has gone missing.</h1><a class="home-link" href="#">Hitch a ride back home.</a>
  </div>
  <div class="ground">
    <div class="mound"> 
      <div class="mound_text">404</div>
      <div class="mound_spade"></div>
    </div>
  </div>
</div></div>
</template>

<script>
export default {
  name: "Fargo404",
  created() {},
  mounted() {
    let externalScript = document.createElement('script')
    externalScript.setAttribute('src', './script.js')
    document.head.appendChild(externalScript)
  },
  data() {
    return {};
  },
  props: {},
  methods: {},
};
</script>

<style lang="css" scoped>
@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
@import url("https://fonts.googleapis.com/css?family=Dosis:400,300,500,800");
@import url("./style.css");
</style>