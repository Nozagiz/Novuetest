<template >
<div>
  <img alt="Vue logo" src="./assets/logo2.png">
  <h3><HelloWorld msg="Welcome to My world"/></h3>
  <h5><HelloWorld msg="Nutchanon  Thawornnuruk" major="Information Technology and Digital Innovation"/></h5>
  <br/>
  <button @click="counter += 1"> Add 1</button> 
  <p>The button above has been clicked {{ counter }} times.</p>
  <input v-model="message" placeholder="enter">
  <p>Message is: {{ message }}</p>
 </div> 
  
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  },
  data() {
    return {
      counter:0,
      message:""
    }
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
