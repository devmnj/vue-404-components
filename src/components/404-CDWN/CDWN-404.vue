<template>
  <div>
    <section class="content">
      <div class="planet"></div>
      <div class="astronauta"></div>
      <div class="text">
        <h1>Ooops!</h1>
        <h2>Parece que desta vez você foi longe.</h2>
        <h3>
          Não se preocupe. Traremos você de volta em <span id="countdown">10</span>s.
        </h3>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: "CD404",
  created() {},
  data() {
    return {};
  },
  mounted() {
    let externalScript = document.createElement('script')
    externalScript.setAttribute('src', './script.js')
    document.head.appendChild(externalScript)
  },
  props: {},
  methods: {},
};
</script>

<style lang="css" scoped>

@import url("./style.css");
@import url("https://cdnjs.cloudflare.com/ajax/libs/normalize/5.0.0/normalize.min.css");

</style>
