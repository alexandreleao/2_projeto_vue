<template>
<div>
  <PrimeiroComponente/>
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

  import PrimeiroComponente from './components/PrimeiroComponente.vue'
  import TesteComponente from  './components/TesteComponente.vue'
  import FormComponente from './components/FormComponente.vue'
  import ListaComponente from './components/ListaComponente.vue'
  import LifeCycle from './components/LifeCycle.vue'
  import Pessoa from './components/Pessoa.vue'
  
 
  
    export default{
      name: 'App',
      components:{
          PrimeiroComponente,
          TesteComponente,
          FormComponente,
          ListaComponente,
          LifeCycle,
          Pessoa
      },
     
    }    

</script>