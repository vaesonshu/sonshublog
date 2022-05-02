<template>
  <div>
    <MyHeader />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import MyHeader from './views/header/header.vue'
export default defineComponent({
  name: 'App',
  components: {
    MyHeader
  }
})
</script>

<style lang="less"></style>
