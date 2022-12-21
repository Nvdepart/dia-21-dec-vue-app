<template>
    <div>
        Hola mon {{ nom }}
        <div v-for="persona in noms">{{ persona }}</div>
    </div>
</template>
<script>
export default{
    props:['nom'],
    data(){
        return {
            noms:["Jordi", "Laura", "David"]
        }
    }
}
</script>