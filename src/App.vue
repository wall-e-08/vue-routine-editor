<template>
  <div id="app">
    <!--<img src="./assets/logo.png">-->
    <RoutineBoard/>
  </div>
</template>

<script>
import RoutineBoard from './components/RoutineBoard'

export default {
    name: 'App',
    components: {
        RoutineBoard
    }
}
</script>

<style>
#app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
}
</style>
