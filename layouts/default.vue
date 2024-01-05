<template>
  <div>
    <AdminNav />
      <div class="row">
        <div class="sidebar col-md-2">
            <AdminSidebar />
        </div>
        <main class="col-md-8 p-5">
            <slot></slot>
        </main>
    </div>
    <AdminFooter />
  </div>
</template>



