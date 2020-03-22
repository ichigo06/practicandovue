<template>
<div class="container">
 <div class="columna1">
     <div>
         <a href="" class="btn "><b class="bt">{{suma}}</b>{{btn}}</a>
</div>
<div class="col2">
   <p class="parrafo">{{texto}}</p>
</div>
<div>
    
</div>
 </div>
 <div class="columna2">
     <div class="columuna2-1">
          <input class="text" type="text" placeholder=" Laravel">
     <a class="btn1 " href=""><i class="fas fa-star"></i></a>
     <a class="btn2" href=""><i class="fas fa-trash"></i></a>
     </div>
</div>
<div class="columna3"></div>
<div class="columna4"></div>
</div>
</template>
<script>
export default {
    name:'index',
    data() {
        return {
            title: 'Bienvenidos a Media Impact',
            btn: ' Add note',
            texto: 'Larabel',
            suma: '+'
            // parrafo: 'Laravel'
            
        }
     }
}
</script>

<style scoped>

.parrafo {
    display: inline;
    font-family:Arial, Helvetica, sans-serif;
    font-size: 25px;
}
.col2{
    margin: 12px 0;
    padding: 10px;
    background: rgb(64, 184, 131);
    color: #ffffff;
}
.container {
    display: grid;
    grid-template-columns: 25% 50% 0.3% 24.7%;
    height: 100vh;
}
.bt {
    font-family: initial;
    font-size: 30px;
}
.btn {
    padding: 7px 12px 10px 10px;
    background: rgb(64, 184, 131);
    margin-left: 5px;
    margin-top: 5px;
    font-size: 20px;
    text-decoration: none;
    color: #ffffff;
    border-radius: 5px;
    font-family:Arial, Helvetica, sans-serif;
}
.btn1 {
    
    padding: 10px 15px;    
    background: rgb(64, 184, 131);
    margin-left: 5px;
    margin-top: 5px;
    font-size: 20px;
    text-decoration: none;
    color: #ffffff;
    border-radius: 5px;
    font-family:Arial, Helvetica, sans-serif;
}
.btn2 {
    
    padding: 10px 18px;    
    background: rgb(64, 184, 131);
    margin-left: 5px;
    margin-top: 5px;
    font-size: 20px;
    text-decoration: none;
    color: #ffffff;
    border-radius: 5px;
    font-family:Arial, Helvetica, sans-serif;
}
.columna1 {
    background: #f7f7f7;
    padding-top: 12px;
}
.columna2 {
background: #ffffff;
}
.columna3 {
    background: #f7f7f7;
}
.columna4 {
background: #ffffff;
}
.text {
    background: rgb(240, 249, 245);
    border-color: rgb(173, 226, 202);
    padding: 5px;
    margin-left: 5px;
    margin-top: 5px;
    display: inline-block;
}
.columuna2-1 {
    display: flex;
}
.fa .fa-star {
    padding: 60px;
}

</style>