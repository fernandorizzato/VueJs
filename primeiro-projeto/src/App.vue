<template>
  <div id="app">
    <HelloWorld />
    <NovoComponente />
    <SitesFavoritos />
    <TesteEvento />
    <TesteFor />
    <testeif />
  </div>
</template>


<script>
import HelloWorld from "./components/HelloWorld.vue";
import NovoComponente from "./components/NovoComponente.vue";
import SitesFavoritos from "./components/SitesFavoritos.vue";
import TesteEvento from "./components/TesteEvento.vue";
import TesteFor from "./components/TesteFor.vue";
import testeif from "./components/TesteIf.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
    NovoComponente,
    SitesFavoritos,
    TesteEvento,
    TesteFor,
    testeif,
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
