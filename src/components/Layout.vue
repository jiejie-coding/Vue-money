<template>
  <div class="layout-wrapper">
    <div class="content" :class="classPrefix && `${classPrefix}-content`">
      <slot/>
    </div>
    <Nav/>
  </div>
</template>

<script lang="ts">

export default {
  name: 'Layout',
  props: ['classPrefix']
};
</script>

<style lang="scss" scoped>
.layout-wrapper {
  display: flex;
  flex-direction: column;
  height: 100vh;
  //border: 1px solid blue;
}
.content {
  //border: 1px solid red;
  flex-grow: 1;
  overflow: auto;
}
</style>