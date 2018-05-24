<template>
	<header>
		<div class="logo">
			{{test}}
		</div>
		<nav>
			meong
		</nav>
	</header>
</template>

<script>
export default {
  name: "Header",
  props: [],
  data() {
    return {
      test: "miaw"
    };
  }
};
</script>

<style scoped>
header {
  display: flex;
}
</style>