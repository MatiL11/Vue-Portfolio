<template>
  <MainCard />
  <ProjectsCard />
</template>

<script>
import MainCard from "./components/MainCard.vue";
import ProjectsCard from "./components/ProjectsCard.vue";

export default {
  name: "App",
  components: {
    MainCard,
    ProjectsCard,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background-color: #f1d7ff;
  min-height: 100vh;
}

html,
body {
  margin: 0;
  padding: 0;
  height: 100%;
}
</style>
