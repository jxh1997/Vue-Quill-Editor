<template>
  <div id="app">
    <QuillEditor/>
  </div>
</template>

<script>
import QuillEditor from './components/QuillEditor.vue'

export default {
  name: 'App',
  components: {
    QuillEditor
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
