<template>
  <div id="app">
    <div id="nav">
      <helloworld></helloworld>


    </div>

  </div>
</template>

<script>
    import helloworld from './components/HelloWorld.vue'
    export default {
        name: 'app',
        components: {
            helloworld,
        }
    }
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 0px;
}
</style>
