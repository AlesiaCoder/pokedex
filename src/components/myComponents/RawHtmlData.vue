<script>
export default {
    data(){
        return{
            title: "This is my title for Monday",
            person:{
                id: 1,
                name : 'Bill',
                img : "https://www.ecured.cu/images/0/0a/Atrapado_en_el_tiempo_%28Pel%C3%ADcula%29.jpg",
            },
            msg: "Bill uno de los integrantes de los cazafantasmas",
        }
    },
};
</script>


<template>
    <h3>{{ title }}</h3>
    <div :id="person.id"> 
        <h4>{{ person.name }}</h4>
        <img :src="person.img" :alt="person.name">
    </div>
    <h5 v-html="msg"></h5>
</template>


<style lang="css" scoped>
h3 {
    color:magenta;
}
</style>