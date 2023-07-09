<template>
  <div class="container">
    <left-side-bar />
    <div class="main">
      <p v-for="el in 20" :key="el">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Beatae, earum
        minima voluptas.
      </p>
    </div>
    <right-side-bar />
  </div>
</template>

<script>
import LeftSideBar from "@/components/common/sidebar/LeftSideBar.vue";
import RightSideBar from "@/components/common/sidebar/RightSideBar.vue";
export default {
  components: { LeftSideBar, RightSideBar },
};
</script>

<style lang="scss" scoped>
</style>