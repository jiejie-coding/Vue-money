<template>
  <Layout class-prefix="layout">
    <Types/>
    <Tags/>
    <Notes/>
    <NumberPad/>

  </Layout>
</template>

<script lang="ts">

import NumberPad from '@/components/Money/NumberPad.vue';
import Types from '@/components/Money/Types.vue';
import Notes from '@/components/Money/Notes.vue';
import Tags from '@/components/Money/Tags.vue';
export default {
  name: 'Money',
  components: {Tags, Notes, Types, NumberPad},
};
</script>

<style lang="scss">
  .layout-content {
    display: flex;
    flex-direction: column;
  }
</style>


<style lang="scss" scoped>



</style>