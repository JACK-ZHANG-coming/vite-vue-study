<script setup>
import { ref } from 'vue'
// import Button from 'ant-design-vue/lib/button'
// import 'ant-design-vue/lib/button/style/css' // 或者 ant-design-vue/lib/button/style/css 加载 css 文件

defineProps({
  msg: String
})

const count = ref(0)
</script>

<template>
  <h1>{{ msg }}</h1>

  <p>
    Recommended IDE setup:
    <a href="https://code.visualstudio.com/" target="_blank">VS Code</a>
    +
    <a href="https://github.com/johnsoncodehk/volar" target="_blank">Volar</a>
  </p>

  <p>
    <a href="https://vitejs.dev/guide/features.html" target="_blank"> Vite Documentation </a>
    |
    <a href="https://v3.vuejs.org/" target="_blank">Vue 3 Documentation</a>
  </p>

  <button type="button" @click="count++">count is: {{ count }}</button>
  <p>
    Edit
    <code>components/HelloWorld.vue</code> to test hot module replacement.
  </p>

  <a-button type="primary">000000</a-button>
</template>

<style scoped>
a {
  color: #42b983;
}
</style>
