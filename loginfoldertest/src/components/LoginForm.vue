<template>
  <div id="LoginForm">
    <h2>Registration Form</h2>

    <form>
      <!-- Name -->
      <label for="fname">First name:</label>
      <input type="text" id="fname" name="fname" placeholder="John" />
      <label for="lname">Last name:</label>
      <input type="text" id="lname" name="lname" placeholder="Doe" />
      <br />
      <br />

      <!-- Email and password -->
      <label for="email">Email:</label>
      <input type="text" id="email" name="email" placeholder="example@example.com" />
      <label for="password">Password:</label>
      <input type="password" name="password" id="password" />
      <br />
      <br />

      <!-- Adress Stuff -->
      <label for="address">Address:</label>
      <input type="text" id="address" name="address" />
      <label for="postalcode">Postal Code:</label>
      <input type="text" id="postalcode" name="postalcode" />
      <br />
      <br />
    </form>

    <button type="submit">Register</button>
  </div>
</template>

<script>
export default {
  name: "LoginForm",
  props: {
    msg: String
  }
};
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

input, form {
  font-family: Arial, Helvetica, sans-serif;
  font-weight: 200; 
}

</style>
