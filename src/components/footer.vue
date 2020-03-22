<template>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
      <header>
        <h3>{{ title }}</h3>
    </header>


</body>
</html>
    
</template>
<script>

export default {
    name:'footer',
    data() {
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