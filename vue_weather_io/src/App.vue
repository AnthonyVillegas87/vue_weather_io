

<template>
  <div class="app">
    <div class="header container h-100 p-5">
      <h1 class="mb-5">
        Weather Vue
      </h1>
      <div class="d-flex justified-content-center h-35">
        <div class="searchbar w-125 mx-2">
          <input type="text" class="input form-control" placeholder="Enter a city">
        </div>
        <button class="btn-search btn btn-info">Search <i class="fas fa-search"></i></button>
      </div>
    </div>
  </div>
</template>

<script>
export default (await import('vue')).defineComponent({
  name: 'App',
  components: {

  }
})
</script>

<style scoped>

</style>
