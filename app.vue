<template>
  <!-- <div>
    {{ res }}
  </div> -->
  <NuxtLink to="/">首页</NuxtLink>
  <NuxtLink to="/news">新闻页</NuxtLink>
  <NuxtPage></NuxtPage>
</template>
<script setup lang="ts">
  // const res = await $fetch('http://localhost:8888/api/private/v1/login',
  // {
  //   method: 'POST',
  //   body: { username: 'admin', password: '123456' }
  // })
</script>