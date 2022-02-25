<template>
    <h1>Lista de Usuários</h1>
    <ul>
        <li>{{ ListaNome }}</li>
    </ul>
</template>

<script>
export default{
    name: 'Lista de Usuários',
    data(){
        return{
           
            ListaNome: "João, José, Maria"
        }
    }
}

</script>