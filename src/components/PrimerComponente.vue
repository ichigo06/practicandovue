<template>
<div>
  <h1 ref="mainElement">{{message}}</h1>
  <button @click="ChangeMessaged">Cambiar</button>
  <button @click="$destroy()">Destruir Componente</button>
</div>
</template>
<script>
export default {
    name:'PrimerComponent',
    data () {
      return {
        message: 'Hola'
      }
    },
    methods: {
      ChangeMessaged() {
        this.message = 'Hello'
      }
    },
    beforeCreate () {
      console.error('Estoy beforeCreate')
      console.error(this.message)
    },
    created () {
      console.error('Estoy en Create')
      console.error(this.message)
    },
    beforeMount () {
      console.log('Estoy en beforeMount')
      console.log(this.$refs)
      console.log(this.$refs.mainElement)
    },
    mounted() {
      console.log('Estoy en mounted')
      console.log(this.$refs)
      console.log(this.$refs.mainElement)
    },
    beforeUpdate() {
      console.log('Estoy en beforeUpdate')
      console.log(this.$refs.mainElement)
    },
    updated() {
      console.log('Estoy en update')
      console.log(this.$refs.mainElement)
    },
    beforeDestroy() {
      console.log('Estoy en beforeDestroy')
      console.log(this.message)
    },
    destroyed() {
      console.log('Estoy en update')
      console.log(this.message)
    },
}
</script>
<style>

</style>