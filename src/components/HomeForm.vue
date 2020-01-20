<template>
  <!-- Default form contact -->
  <form id="user-form" action="http://localhost:8000/api/users" method="post">
    <p class="h4 text-center mb-4">Add user info: </p>
    <!-- Default input name -->
    <label for="defaultFormContactNameEx" class="grey-text">Your name</label>
    <input type="text" id="defaultFormContactNameEx" class="form-control" name="name">
    <br>

    <!-- Default input phone -->
    <label for="defaultFormContactPhoneEx" class="grey-text">Your Phone</label>
    <input type="phone" id="defaultFormContactPhoneEx" class="form-control" name="phone">

    <br>

    <!-- Default input email -->
    <label for="defaultFormContactEmailEx" class="grey-text">Your email</label>
    <input type="email" id="defaultFormContactEmailEx" class="form-control" name="email">

    <br>

    <!-- Default input ImageURL -->
    <label for="defaultFormContactImageURLtEx" class="grey-text">Image URL</label>
    <input type="text" id="defaultFormContactImageURLEx" class="form-control" name="image_url">

    <br>

    <div class="text-center mt-4">
        <button class="btn btn-outline-warning" type="submit">Send<i class="far fa-paper-plane ml-2"></i></button>
    </div>
  </form>
  <!-- Default form contact -->
</template>

<script>
export default {
  name: 'HomeFrom',
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
</style>
