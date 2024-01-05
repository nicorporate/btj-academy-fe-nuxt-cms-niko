<template>
    <nav>
      <div class="d-flex nav-top align-items-center logo px-5">
        <div class="me-auto p-2">
          <h3 id="welcome">Welcome</h3>
        </div>
        <div class="p-4 nav-item d-flex flex">
          <nuxt-link class="nav-link mx-2" to="/">Home</nuxt-link>
          <nuxt-link class="nav-link" to="/login">Login</nuxt-link>
        </div>
    </div>
    </nav>
</template>

<script>
export default {

}
</script>

<style>
@import url('https://fonts.googleapis.com/css?family=Montserrat');




.navbar-toggler{
    border: 0px;
}


</style>