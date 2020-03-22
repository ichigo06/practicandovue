<template>
<div>
  <Header />
  <Index />
  <Footer />  
</div>
</template>
<script>  
import Header from './components/header'
import Index from '../view/index'
import Footer from './components/footer';



export default {
  name: 'app',
   components: {
    Header,
    Index,
    Footer
 
  
}

}
</script>

<style>

</style>
