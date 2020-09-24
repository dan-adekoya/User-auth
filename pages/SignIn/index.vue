<template>
  <div class="container">
    <form>
      <h2>Sign In.</h2>
      <input type='text' placeholder="Name.">
      <input type='password' placeholder="Password.">
      <input class="submit" type='button' value="Enter">
      <p>Don't have an account? <nuxt-link to='/'>Sign Up</nuxt-link></p>
    </form>
  </div>
</template>

<script>
export default {
  name: 'index',
  data() {
    return {
      
    }
  },
  methods: {
    
  },
}
</script>

<style scoped>
h2{
  margin-bottom: 30px;
  font-weight: 400;
}
form{
  text-align: center;
  width: 450px;
  margin: 50px auto;
  padding: 40px;
  border: 4px solid #00C48D;
  border-radius: 10px; 
}
form input{
  width: 100%;
  padding: 15px;
  margin: 10px 0;
  border: 2px solid #E2E2E2;
  outline: none;
  border-radius: 10px
}
::placeholder{
  color: #E2E2E2;
}
form .submit{
  margin: 20px 0;
  opacity: 100%;
  background: #00C48D;
  border: 2px solid #00C48D;
  color: #FFFFFF;
  font-size: 20px;
  cursor: pointer;
}
a{
  color: #00C58E;
  text-decoration: none;
}
@media screen and (max-width: 500px){
  form{
    width :90%;
  }
}
</style>
