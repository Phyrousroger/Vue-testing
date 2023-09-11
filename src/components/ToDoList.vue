<template>
  <div class="m3">
    <h3>Expense Tracker</h3>
    <form action="">
      <div class="row">
        <div class="col-4">
          <div class="form-floating">
            <input type="text" close="form-control" id="email">
            <label for="email">What did you use?</label>
          </div>
        </div>
        <div class="col-4">

        <div class="form-floating">
          <input type="number" close="form-control" id="price">
          <label for="price">How did you use?</label>
          </div>
        </div>
        </div>
        <div class="col-4">
        <div class="form-floating">
          <button class="btn btn-lg btn-primary h-100">Add</button>
        </div>
        </div>

  </form>
  </div>

</template>

<script>
export default {

}
</script>

<style scoped>

</style>