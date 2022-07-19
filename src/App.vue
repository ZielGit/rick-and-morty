<template>
  <div>
    <h1>Rick And Morty</h1>
    <listCharacters />
  </div>
</template>

<script>
import ListCharacters from './components/ListCharacters.vue'

export default {
  name: 'App',
  components: {
    ListCharacters
    
  }
}
</script>

<style lang="scss">

</style>
