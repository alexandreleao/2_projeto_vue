<template>
    <h1>Formulário de Cadastro</h1>
    <p>Cadastre-se {{ Cadastrar }}</p>
</template>


<script>
 export default{
     name: 'Esse é o formulário de cadastro vuejs',
     data(){
         return{
             Cadastrar: "Aqui é o local do seu form de cadastro"
         }
     }
 }

</script>