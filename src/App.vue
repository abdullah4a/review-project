<template>
  <div>
    <nav-bar/>
    <home-view/>
    <footer-component/>
  </div>
</template>

<script>
import FooterComponent from './components/common/footer/FooterComponent.vue';
import NavBar from './components/common/nav/NavBar.vue';
import HomeView from './views/homeview/HomeView.vue';
export default {
  name: "App",
  components: {
    NavBar,
    HomeView,
    FooterComponent
  },
};
</script>