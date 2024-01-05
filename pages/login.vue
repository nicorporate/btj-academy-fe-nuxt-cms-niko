<template>
  <div class="container">
  <div class="row">
    <div class="col d-flex justify-content-center my-5">
      <div class="p-5 my-5">
          <FormLogin />
        </div>
    </div>
  </div>
  </div>
</template>

<script>
definePageMeta({
  layout:'auth'
})
</script>

<style scoped>
@media (max-width: 768px) {
  .box {
    width: 85%;
  }
}

@media screen and (min-width : 768px) and (max-width : 1024px) {
  .box {
    width: 70%;
  }
}
</style>
