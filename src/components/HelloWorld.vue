<template>
  <div class="hello">
    <br>
    <h1>hej, det är jag som är lillpelle</h1>
    <div> hoppas du har en helt OK dag.
      <br>
      <br>
      <a target="_blank" href="https://www.youtube.com">videos</a>
      <h3>{{ msg }}</h3>
      <br>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}

a {
  color: rgb(255, 0, 13);
}
</style>
