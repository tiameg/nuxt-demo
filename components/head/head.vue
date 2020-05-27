<template>
  <div class="header">
    <nuxt-link
      class="header-item"
      to="/index"
    >首页</nuxt-link>
    <nuxt-link
      class="header-item"
      to="/about"
    >关于我们</nuxt-link>
  </div>
</template>

<script>
  import head from "./head.js";
  export default head;
</script>
