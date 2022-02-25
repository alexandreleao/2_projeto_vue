<template>
<div>
 <h1>Olá, meu nome é: {{nome}}!</h1>
 <p>E a minha Profissão é: {{ profissao }}</p>
</div>
</template>


<script>
export default {
    name: 'PrimeiroComponente',
    data(){
        return{
            nome: "Alexandre",
            profissao: "Programador"
        }
    }
}
</script>
