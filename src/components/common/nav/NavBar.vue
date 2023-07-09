<template>
  <nav class="nav">
    <ul class="nav-bar">
      <li class="nav-items" v-for="(menu, index) in titles" :key="index">
        {{ menu }}
      </li>
    </ul>
  </nav>
</template>

<script>
export default {
  props: {
    titles: {
      type: Array,
      required: true,
    },
  },
};
</script>

<style lang="scss" scoped>
</style>