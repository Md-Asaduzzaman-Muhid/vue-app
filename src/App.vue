<template>
  <div id="form-section">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <!-- <HelloWorld msg="Welcome to Your Vue App"/> -->
    <HomeForm />
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import HomeForm from './components/HomeForm.vue'

export default {
  name: 'form-section',
  components: {
    HomeForm
  }
}
</script>

<style>
#form-section {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
