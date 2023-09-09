<script setup>

</script>

<template>
  <div>
    You have deployed a Vue project with element UI.
  </div>
  <div>
    <el-button @click="show()">Test</el-button>
  </div>
</template>

<style scoped>

</style>

<script>
export default {
  name: 'TestElementUI',
  components: {},
  methods:{
    show() {
      console.log("UI successful");
    },
  },
}
</script>