<template>
<header>
        <h3>{{ title }}</h3>
       </header>
</template>
<script>

export default {
    name:'header',
    data () {
        return {
            title: 'Bienvenidos a Media Impact'
        } 
     }
}
</script>

<style scoped>
* {
    margin: 0;
    padding: 0;
}
    header {
        
        background-color: black;
        padding: 15px;
        height: 50px;
        text-align: center;
       
        
    }
</style>