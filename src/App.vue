<template>
  <div id="app" class="container">
    <Search />
    <List />
  </div>
</template>

<script>
import Search from "./components/Search.vue";
import List from "./components/List.vue";
export default {
  name: "App",
  components: {
    Search,
    List,
  },
  data() {
    return {};
  },
};
</script>


<style scoped>
</style>