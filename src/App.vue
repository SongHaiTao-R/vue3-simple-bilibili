<template>
  <div class="contain">
    <span @click="skipHome">{{ homeView }} | </span>
    <span @click="skipAbout">homeAbout |</span>
    <RouterView/>
  </div>
</template>

<script setup lang="ts">
import { useRouter } from 'vue-router'
import { ref } from 'vue'

const router = useRouter()
const homeView = ref('homeView')

function skipAbout() {
  router.push({ path: '/about' })
}

function skipHome() {
  router.push({ path: '/' })
}
</script>

<style lang="less">
.contain {
  span {
    // font-size: 20px;
  }

}
</style>
