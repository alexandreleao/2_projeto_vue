<template>
    <div>
<p v-if="esta_trabalhando">Estou trabalhando no momento.</p>
<p v-else>Estou em busca de novas oportunidades!</p>
    <p>E uso as seguintes tecnologias:</p>
        <ul>
          <li>Javascript</li>
          <li>Php</li>
          <li>Python</li>
        </ul>
        <p v-show="mostrar_email">Mande uma mensagem para: {{ email }}</p>
    </div>
</template>

<script>
  export default{
      name: 'Info',
      data(){
        return{
          esta_trabalhando: false,
          mostrar_email: true,
          email: 'alexandre@teste.com'
        }
      }
  }

</script>