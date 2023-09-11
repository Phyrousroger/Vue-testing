<template>
  <div class="m-3 p-3">
    <button @click="showBox=false" class="btn btn-primary">Hide</button>
    <div v-if="showBox" class="border border-primary mt-3 p-3 rounded">
      Lorem ipsum dolor sit amet, consectetur adipisicing elit. Alias dolore eligendi facilis ipsa magnam minus non perferendis possimus, repellendus totam? Assumenda culpa expedita facere, ipsa nobis perferendis quasi quisquam rerum.
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      showBox: true,
    }
  },
}
</script>

<style scoped>

</style>