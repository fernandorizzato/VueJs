<template>
  <div class="teste-for">
    <h2>Teste For</h2>
    <ul>
      <li v-for="animal of animais" v-bind:key="animal.id">
        <img v-bind:src="animal.url" v-bind:alt="animal.nome" />
      </li>
    </ul>
  </div>
</template>

<script>
export default {
   name: 'TesteFor',
   data () {
       return {
           animais : [
               {   id: 1, 
                   nome: 'Gatinho',
url: 'https://th.bing.com/th/id/OIP.5Gz5cG8TOZFfX1rEq15gJgHaHa?pid=ImgDet&rs=1'
               },
                {
                    id: 2,
                   nome: 'Cachorrinho',
url: 'https://th.bing.com/th/id/R.f740c03fea7fb2701e42c6c11a7bddde?rik=YXajPqMiU3kwIg&riu=http%3a%2f%2ftudosobrecachorros.com.br%2fwp-content%2fuploads%2fcachorro-independente.jpg&ehk=048Jj%2bYRRmKgqBXuwnE%2f7rOXk3sj%2fWayJEsb5UIA5AI%3d&risl=&pid=ImgRaw&r=0'
               }
           ]
       }
   }    
}
</script>

<style scoped>
</style>
