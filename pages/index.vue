<template>
  <div>
    <div class="diss"></div>
    <ul>
      <li><nuxt-link :to="{name:'index'}">HOME</nuxt-link></li>
      <li><nuxt-link :to="{name:'about'}">ABOUT</nuxt-link></li>
      <li><nuxt-link :to="{name:'news',params:{newsId:3306}}">NEWS</nuxt-link></li>
      <li><nuxt-link :to="{name:'ansycData'}">ansycData</nuxt-link></li>
    </ul>
  </div>
</template>

<script>

export default {
  components: {
  }
}
</script>

<style>
  .diss{
    width: 600px;
    height: 400px;
    background-image: url("~static/scren.jpg");
  }
</style>
