<template>
  <section>
    <div>{{ name }}</div>
    <a-button>你好</a-button>
  </section>
</template>

<script lang="ts" setup>
import { ref } from 'vue'

const name = ref('About')
</script>

<style scoped lang="less">

</style>
