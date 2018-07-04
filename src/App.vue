<template>
  <div id="app">
    <HelloWorld msg=" - ha det bäst, homeslice."/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';

export default {
  name: 'app',
  components: {
    HelloWorld,
  },
};
</script>

<style>

#app {
  background-color: black;
  font-family: "Lucida Console", "Lucida Sans Typewriter", monaco, "Bitstream Vera Sans Mono", monospace;
  text-align: center;
  color: white;
  margin-top: 200px;
}
</style>
