<template>
  <section>
    <div>{{ name }}</div>
    <a-button>世界</a-button>
  </section>
</template>

<script lang="ts" setup>
import { ref } from 'vue'

const name = ref('Home')
</script>

<style scoped lang="less">

</style>
