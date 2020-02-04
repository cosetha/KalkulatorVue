<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <h1>Cosetha Aberoa</h1>
     <section class="calculator" id="calculator">
      <Calculator></Calculator>
    </section>
    <input v-model="message" placeholder="edit me">
  </div>
</template>

<script>
import Calculator from './components/Calculator.vue'
export default {
  name: 'app',
  components: {
    Calculator
  },
  data(){
    return({
      message: 'sada kala kulo',
    });
  },
};
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.calculator{
  margin-top:  30px;
  border: 0.8rem solid #FF4500;
  width: 34rem;
  height: 40rem;
  background-color: #FF4500;
  font-size: 1.6rem;
   margin: 2.5rem auto;
}

</style>
