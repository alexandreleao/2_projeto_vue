<template>
    <div>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">Projetos</a></li>
            <li><a href="#">Contato</a></li>
        </ul>
    </div>
</template>


<script>

export default{
    name:'Header',
    
}

</script>

<style scoped>
ul{
    background: #111;
    list-style:none;
    display:flex;
}

li{
    margin-right:10px;
}
a{
    color: #DDD;
    text-decoration:none;
    transition: .5s;

}

a:hover{
    color:turquoise;
}

</style>