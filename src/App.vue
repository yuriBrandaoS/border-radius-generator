<template>
  <div id="app">
    <Title />
    <Box />

  </div>
</template>

<script>
import Title from './components/Title.vue';
import Box from './components/Box.vue';


export default {
  name: 'App',
  components: {
    Title,
    Box,
  }
}
</script>

<style>
@import './assets/style.css';
</style>
