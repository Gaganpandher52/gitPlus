<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>Find your GitHub Profile 💁</p>
    <input type="text">
    
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
p{
  font-size: 20px
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
input{
  background-color: rgb(38, 48, 60);
    width: 100%;
    max-width: 400px;
    color: rgb(121, 184, 255);
    font-family: "SF Mono", "Fira Code", "Fira Mono", "Roboto Mono", "Lucida Console", Monaco, monospace;
    font-size: 1.8rem;
    font-weight: 300;
    text-align: center;
    outline: 0px;
    border-width: 0px;
    border-style: initial;
    border-color: initial;
    border-image: initial;
    border-radius: 0.25rem;
    margin: 0px auto;
    padding: 1rem;
}
</style>
