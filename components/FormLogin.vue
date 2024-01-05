<template>
        <h4 class="text-center">Login to Admin</h4>
       <form  class="my-4 form-control p-4">
        <label for="username">Username:</label>
        <br/>
        <div class="">
          <input class="form-control" type="text" id="username" name="username" placeholder="Input Username">
      
        </div>
          <br/>
          <label for="password">Password:</label>
          <br/>
          <div class="">
            <input class="form-control"  type="password" id="password" name="password" placeholder="Input Password">

          </div>
          <br/>
             <button class="btn btn-primary buttonLogin" @click="toHome">Login</button>
        </form>
</template>

<script>
export default {
    methods: {
        toHome(){
            alert("Login Successeful")
            navigateTo('/admin/about')
        }
    }
}
</script>

<style>
input {
  width: 100%

}

.buttonLogin {
  width: 100%;
}
h4{
  color: rgb(40, 40, 40);
}

</style>