<template>
  <div id="app">
    <Header />
    <Navigation />
    <PageDetails />
    <Footer />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Navigation from "./components/Navigation.vue";
import PageDetails from "./components/PageDetails.vue";
import Footer from "./components/Footer.vue";
export default {
  name: "App",
  components: {
    Header,
    Navigation,
    PageDetails,
    Footer,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /* margin-top: 60px; */
}
.title-heading {
  font-family: "Gill Sans", sans-serif;
}
</style>
