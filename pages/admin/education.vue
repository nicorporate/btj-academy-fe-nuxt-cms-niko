<template>
<div class="admin">
  <h3 class="my-5">Education</h3>
  <div class="my-5 mx-2">
    <div class="mb-4">
      <label for="exampleFormControlInput1" class="form-label">University</label>
      <input type="text" class="form-control" id="exampleFormControlInput1" placeholder="...">
    </div>
    <div class="mb-4">
      <label for="exampleFormControlInput1" class="form-label">Major</label>
      <input type="text" class="form-control" id="exampleFormControlInput1" placeholder="...">
    </div>
    <div class="mb-4">
      <label for="exampleFormControlInput1" class="form-label">Year</label>
      <input type="text" class="form-control" id="exampleFormControlInput1" placeholder="...">
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