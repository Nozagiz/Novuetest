<template>
  <div class="hello" >
    <h1>{{ msg }}</h1>
    <h2>{{ major }}</h2>
   <!-- <button @click="counter += 1"> Add 1</button> 
  <p>The button above has been clicked {{ counter }} times.</p> -->
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String,
    major: String,
  },
  // data(){
  //   return {
  //     counter:0
  //   }
  // }
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
</style>
