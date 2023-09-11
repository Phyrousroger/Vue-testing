<template>
  <div>
    <h3 @click="listOpen" :class="{'bg-primary text-white':listDetail.isOpen}" class="text-primary border border-primary p-3 rounded my-2">
      {{ listDetail.title }}
    </h3>
  </div>
    <div :class="{'d-none':!listDetail.isOpen}" class="p-3 my-3">
      {{ listDetail.body }}
    </div>

</template>

<script>
export default {
  data() {
    return {
      //isOpen: this.listDetail.isOpen,
    }
  },
  methods: {
    listOpen() {
      this.isOpen=!this.isOpen
      this.$emit('open',this.listDetail.isOpen,this.listDetail.id)
    }
  },

  props:['listDetail'],
}
</script>

<style scoped>

</style>