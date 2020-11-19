<template>
  <div id="app">
    <header class="h-60 bg-primary d-flex ai-center fs-16">header</header>
    <keep-alive>
      <router-view />
    </keep-alive>
  </div>
</template>

<script>
export default {
  name: "app",
  components: {},
};
</script>

<style lang="stylus" scoped>
.h-60 {
  height: 60px;
}
</style>
