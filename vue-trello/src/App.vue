<template>
  <div id="app">
    <app-eader></app-eader>
    <router-view class="container"/>
    <app-footer></app-footer>
  </div>
</template>

<script>
import AppFooter from '@/components/AppFooter'
import AppHeader from '@/components/AppHeader'

export default {
  components: { AppFooter, AppHeader },
  name: 'App',
}
</script>

<style scoped>
#app {
  box-sizing: border-box;
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #37474f;
  margin: 0 auto;
  padding: 0;
}

.container {
  padding-bottom: 4rem;
}
</style>
