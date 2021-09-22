<template>
  <div>
    <b-button @click="modalShow = !modalShow">CREATE CATEGORY</b-button>

    <b-modal v-model="modalShow">

      
    </b-modal>
  </div>
</template>

<script>
  export default {
    data() {
      return {
        modalShow: false
      }
    }
  }
</script>