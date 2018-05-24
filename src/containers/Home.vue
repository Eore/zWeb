<template>
	<div>
		<!-- <Header/> -->
    <HomeMenu/>
	</div>
</template>

<script>
import Header from "../modules/Header.vue";
import HomeMenu from "../modules/HomeMenu.vue";

export default {
  name: "Home",
  components: {
    Header,
    HomeMenu
  }
};
</script>

<style scoped>
</style>