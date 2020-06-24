<template>
  <div id="app">
    <AppHeader />
    <Home />
    <Menu />
  </div>
</template>

<script>
import Header from './components/Header'
import Home from './components/Home'
import Menu from './components/Menu'


export default {
  name: 'App',
  components: {
    AppHeader: Header,
    Home,
    Menu
  }
}
</script>

<style>

</style>
