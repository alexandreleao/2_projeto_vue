<template>
<div>
  <Header />
  <PrimeiroComponente/>
  <p class="paragrafo-pai">O dado de app é: {{ teste }}</p>
   <TesteComponente/>
   <hr>
   <FormComponente/>
   <hr>
   <ListaComponente/>
   <hr/>
   <LifeCycle/>
   <hr/>
   <Pessoa/>
  </div>
</template>

<script>
  import Header from './components/Header.vue'
  import PrimeiroComponente from './components/PrimeiroComponente.vue'
  import TesteComponente from  './components/TesteComponente.vue'
  import FormComponente from './components/FormComponente.vue'
  import ListaComponente from './components/ListaComponente.vue'
  import LifeCycle from './components/LifeCycle.vue'
  import Pessoa from './components/Pessoa.vue'
 
  
 
  
    export default{
      name: 'App',
      components:{
          Header,
          PrimeiroComponente,
          TesteComponente,
          FormComponente,
          ListaComponente,
          LifeCycle,
          Pessoa
          
      },
     
    }    

</script>

<style>
body{
  background-color:rgb(107, 107, 107);
  color: white
}

a{
  color: red;
}

.teste{
  background-color: black;
  color:white;
}


</style>