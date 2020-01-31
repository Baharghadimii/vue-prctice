<template>
  <div id="app">
    <Header />
    <b-container class="bv-example-row">
      <b-row>
        <QuestionBox />
      </b-row>
    </b-container>
  </div>
</template>

<script>
import QuestionBox from "./components/QuestionBox.vue";
import Header from "./components/Header.vue";

export default {
  name: "app",
  components: {
    QuestionBox,
    Header
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
