<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
    <h1>CI CD 构建成功</h1>
    <h2>GitHub Actions 测试自动化部署</h2>
    <h3>测试本地修改完代码推送到远程仓库 同时action的workflow工作流监听main分支更改重新打包为dist文件部署到gh-pages分支上</h3>
  <!-- <div>
    <a href="https://vitejs.dev" target="_blank">
      <img src="/vite.svg" class="logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a>
  </div> -->
  <HelloWorld msg="Vite + Vue" />
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
