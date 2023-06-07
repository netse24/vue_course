<template>
  <HeaderComponents />
  <!-- <img alt="Vue logo" src="./assets/logo.png" /> -->
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  <h1>{{ title }}</h1>
  <!-- <ul v-for="teacher of teachers" :key="teacher.name">
    <li>{{ teacher.name }}</li>
  </ul> -->
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import HeaderComponents from "./components/HeaderComponents.vue";
export default {
  name: "App",

  data: function () {
    return {
      // title: "Hello World From Cambodia",
      // teachers: [
      //   { name: "Him" },
      //   { name: "Yon" },
      //   { name: "Rady" },
      //   { name: "Ronan" },
      //   { name: "Gareth" },
      //   { name: "Tanguy" },
      //   { name: "Mengheang" },
      // ],
    };
  },
  components: {
    // HelloWorld,
    HeaderComponents,
  },
};
</script>

<style >
* {
  /* padding: ; */
  margin:0px;
  font-family: verdana;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /* margin-top: 60px; */
}

ul > li {
  color: red;
  list-style-type: none;
}
</style>
