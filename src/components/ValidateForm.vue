<template>
  <div class="container">
  <!-- Default form contact -->
    <form id="user-form" @submit.prevent= "postValue()">
      <p class="h4 text-center mb-4">Validation </p>
      <div class="row">
        <div class="col-md-6">
        <!-- Default input name -->
          <label for="defaultFormContactNameEx" class="grey-text">Your name</label>
          <input type="text" id="defaultFormContactNameEx" class="form-control" name="name" v-model="name">
          <br>

          <!-- Default input phone -->
          <label for="defaultFormContactPhoneEx" class="grey-text">Your Phone</label>
          <input type="phone" id="defaultFormContactPhoneEx" class="form-control" name="phone" v-model="phone">
        </div>
        <div class="col-md-6">
          <!-- Default input email -->
          <label for="defaultFormContactEmailEx" class="grey-text">Your email</label>
          <input type="email" id="defaultFormContactEmailEx" class="form-control" name="email" v-model="email">

          <br>

          <!-- Default input ImageURL -->
          <label for="defaultFormContactImageURLtEx" class="grey-text">Image URL</label>
          <input type="text" id="defaultFormContactImageURLEx" class="form-control" name="image_url" v-model="image_url">

        </div>
        <div class="text-center m-3 ">
            <button class="btn btn-outline-warning" type="submit">Send Value<i class="far fa-paper-plane ml-2" v-on:click="resetForm"></i></button>
        </div>
      
      
      </div>
    </form>
    <!-- Default form contact -->
  </div>
</template>

<script>

export default {
  name: 'ValidateForm',
  data(){
    
    return{
      name: '',
      phone: '',
      email: '',
      image_url: ''
    }
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
</style>
