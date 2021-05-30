<template>
  <div><div class="error-page-wrap">
		<article class="error-page gradient">
			<hgroup>
				<h1>404</h1>
				<h2>oops! page not found</h2>
			</hgroup>
			<a href="`${home}`" title="Back to site" class="error-back">back</a>
		</article>
	</div></div>
</template>

<script>
export default {
  name: "C404",
  created() {},
  data() {
    return {home:'#'};
  },
  props: {},
  methods: {},
};
</script>

<style lang="css" scoped>
@import url("./style.css");
</style>