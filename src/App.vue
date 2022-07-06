<template>
  <div id="app" class="app-style">
    <router-view />
  </div>
</template>

<script>
export default {
  name: 'App',
  data() {
    return {}
  }
}
</script>
<style lang="scss" scoped>
.app-style {
  display: flex;
  max-width: 100%;
  // margin-left: auto;
  // margin-right: auto;
}
</style>

