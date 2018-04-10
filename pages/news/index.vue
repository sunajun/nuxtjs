<template>
  <div>
    <h2>News Index page</h2>
    <p>NewsId:{{$route.params.newsId}}</p>
    <ul>
      <li><a href="/">Home</a></li>
      <li><a href="/news/1a23">News-1</a></li>
      <li><a href="/news/456">News-2</a></li>
      <li><nuxt-link :to="{name:'news-id',params:{id:123}}">News-1</nuxt-link></li>
    </ul>
  </div>
</template>

<script>

</script>

<style scoped>

</style>
