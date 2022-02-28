<template>
    <div>
        <h1>Meu nome é: {{ nome }}</h1>      
    </div>
</template>

<script>

export default{
    name: 'LifeCycle', 
    data(){
        return{
            nome: 'Ainda Não sei'
        }
    },
    created(){                    /*Ciclo de vidas e seus Métodos */
        setTimeout(() => {
            this.nome = 'Matheus'
        }, 1000);
        this.lifeCycle()
    },

    mounted(){
        setTimeout(() => {
           this.nome = ' Antôny'
        }, 2000);
         this.lifeCycle()
    }, 
    methods:{
        lifeCycle(){
            console.log("Executou");
        }
    }

}

</script>