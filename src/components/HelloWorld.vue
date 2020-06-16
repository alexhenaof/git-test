<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      For a guide and recipes on how to configure / customize this project,<br>
      check out the
      <a href="https://cli.vuejs.org" target="_blank" rel="noopener">vue-cli documentation</a>.
    </p>
    <h3>Installed CLI Plugins</h3>
      <p>Soy un texto inicial que debo existir por el momento</p>
    <div>
      <img src="https://source.unsplash.com/1220x600/?dogs" alt="photo" title="random p">
    </div>
    <div class="imagesx">
      <div>
        <img src="https://source.unsplash.com/408x500/?dogs" alt="photo" title="random photo nature">
      </div>
      <div>
        <img src="https://source.unsplash.com/408x500/?dogs" alt="photo" title="random photo water">
      </div>
      <div>
        <img src="https://source.unsplash.com/408x500/?dogs" alt="photo" title="random photo dog">
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
  .imagesx{
    display: flex;
  }
</style>
