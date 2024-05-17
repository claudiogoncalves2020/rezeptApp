<template>
  <Header></Header>
  <RecipeItem></RecipeItem>
  <router-view />
</template>

<script>
import Header from "./components/Header.vue";
import RecipeItem from "./components/RecipeItem.vue";
import HomeViewVue from "./views/HomeView.vue";

export default {
  components: {
    Header,
    RecipeItem,
  },
};
</script>

<style>
body {
  margin: 0;
}

input {
  border: 0;
  border-radius: 8px;
  width: 100%;
  height: 30px;
}
</style>
