<template>
  <div class="sites-favoritos">
    <h2 class="red">Sites Favoritos</h2>
    <ul>
      <li v-for="site of sitesFavoritos" :key="site.id">
        <a href="site.link">{{ site.nome }}</a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "SitesFavoritos",
  data() {
    return {
      sitesFavoritos: [
        {
          id: 1,
        nome: 'Google',
        link: 'https://google.com'
        },
        {
          id: 2,
        nome: 'Youtube',
        link: 'https://youtube.com'
        },
        {
          id:3,
        nome: 'Github',
        link: 'https://Github.com'
        }
      ]
    } 
  }
};
</script>

<style scoped>
.red {
  color: red;
}
</style>