<template>
  <EuropeMap msg="Europe" />
  <TestChart />
</template>

<script>
import TestChart from "./components/TestChart.vue";
import EuropeMap from "./components/EuropeMap.vue";

export default {
  name: "App",
  components: {
    EuropeMap,
    TestChart,
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
  margin-top: 60px;
}
</style>
