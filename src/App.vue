<template>
  <div id="form-section">
    <ValidateForm />
    <HomeForm />
    <UserList />
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import HomeForm from './components/HomeForm.vue'
import UserList from './components/UserList.vue'
import ValidateForm from './components/ValidateForm.vue'

export default {
  name: 'form-section',
  components: {
    HomeForm,UserList,ValidateForm
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
