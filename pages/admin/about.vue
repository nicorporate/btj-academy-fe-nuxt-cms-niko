<template>
<div class="admin">
  <h3 class="my-5">About Me</h3>
  <div class="my-5 mx-2">
    <div class="mb-3">
      <label for="exampleFormControlTextarea1" class="form-label">Tell Us About Yourself</label>
      <textarea class="form-control" id="exampleFormControlTextarea1" rows="3" placeholder="..."></textarea>
    </div>
    <button class="btn btn-primary">Update</button>
  </div>
</div>
  
</template>

<script>
definePageMeta({
  layout:'default'
})
</script>

<style>
.form-label,
.admin {
  color: rgb(42, 61, 158) !important ; 

}
</style>