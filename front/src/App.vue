<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<script>
    import './App.scss'
    export default {
      name: 'app',
      data () {
        return {
          // username:window.localStorage.getItem('obj'),
        }
      }
    }
</script>
