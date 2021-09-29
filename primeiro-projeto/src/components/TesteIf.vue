<template>
  <div class="teste-if">
    <h1 v-if="podeVer">Teste 1</h1>
    <h1 v-else>Teste 2</h1>
  </div>
</template>

<script>
export default {
  name: "testeif",
  data() {
    return {
      podeVer: false,
    };
  },
};
</script>

<style scoped>
</style>
