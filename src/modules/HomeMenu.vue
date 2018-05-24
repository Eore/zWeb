<template>
  <div class="home-menu">
    <div class="vertical">
      <div class="horizontal">
        <a v-for="el in list" :key="el" class="menu" :href="el.link">
          <i :class="'fa fa-' + el.icon"></i>
          <div>{{ el.name }}</div>
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HomeMenu",
  data() {
    return {
      list: [
        { name: "miaw", icon: "user-md", link: "#" },
        { name: "meong", icon: "user-md", link: "#" },
        { name: "nyaan", icon: "user-md", link: "#" },
        { name: "nyaaaa", icon: "user-md", link: "#" }
      ]
    };
  }
};
</script>

<style scoped>
.vertical {
  display: flex;
  flex-direction: column;
}

.horizontal {
  display: flex;
}

.horizontal > a:nth-child(odd) {
  background-color: #f48642;
}

.horizontal > a:nth-child(even) {
  background-color: #fda067;
}

.menu {
  font-size: 1.5em;
  padding: 10px;
  width: 100px;
  height: 100px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
</style>