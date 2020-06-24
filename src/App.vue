<template>
  <div id="app">
    <AppHeader />
    <Home />
  </div>
</template>

<script>
import Header from './components/Header'
import Home from './components/Home'

export default {
  name: 'App',
  components: {
    AppHeader: Header,
    Home
  }
}
</script>

<style>

</style>
