<template>
  <div class="nav-wrapper">
    <div class="content">
      Statistics.vue
    </div>
    <Nav/>
  </div>
</template>

<script lang="ts">
export default {
name: "Statistics",
}
</script>

<style lang="scss" scoped>
.nav-wrapper {
  display: flex;
  flex-direction: column;
  height: 100vh;
  border: 1px solid blue;
}
.content {
  border: 1px solid red;
  flex-grow: 1;
  overflow: auto;
}
</style>