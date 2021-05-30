<template>
  <div>  <div class="error">
                <div class="container-floud">
                    <div class="col-xs-12 ground-color text-center">
                        <div class="container-error-404">
                            <div class="clip"><div class="shadow"><span class="digit thirdDigit"></span></div></div>
                            <div class="clip"><div class="shadow"><span class="digit secondDigit"></span></div></div>
                            <div class="clip"><div class="shadow"><span class="digit firstDigit"></span></div></div>
                            <div class="msg">OH!<span class="triangle"></span></div>
                        </div>
                        <h2 class="h1">Sorry! Page not found</h2>
                    </div>
                </div>
            </div></div>
</template>

<script>
export default {
  name: "OH404",
  created() {},
  data() {
    return {};
  },
  props: {},
  methods: {},
  mounted() {
    let externalScript = document.createElement('script')
    externalScript.setAttribute('src', './script.js')
    document.head.appendChild(externalScript)
  },
};
</script>

<style lang="css" scoped>
@import url("./style.css");
@import url("https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css");
@import url("https://fonts.googleapis.com/css?family=Anton|Passion+One|PT+Sans+Caption");
</style>