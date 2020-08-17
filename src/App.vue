<template>
  <div id="app">
    <Menu/>
    <img alt="Vue logo" src="./assets/logo.png">
    <Counter/>
  </div>
</template>

<script>
import Counter from './components/Counter/Counter.vue'
import Menu from './components/Menu/Menu.vue'
export default {
  name: 'App',
  components: {
    Counter, Menu
  }
}
</script>

<style>

</style>
