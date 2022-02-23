<template>
<div> 
  <h1>Olá, Salvador!</h1>
  <p>{{Teste}}</p>
</div>
 
</template>

<script>
export default{
    name: 'TesteComponente',
    data(){
      return{
        Teste: "Testando Aplicação!"
      }
    }
    
}

</script>