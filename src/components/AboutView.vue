<template>
  <section>
    <div>{{ name }}</div>
  </section>
</template>

<script lang="ts" setup>
import { ref } from 'vue'

const name = ref('About')
</script>

<style scoped lang="less">

</style>
