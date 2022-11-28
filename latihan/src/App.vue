<template>
  <div id="app">
    <Navbar></Navbar>
    <Breadcrumb></Breadcrumb>
    <Galley></Galley>
    <Slider></Slider>
    <Footer></Footer>
    <Copyright></Copyright>
  </div>
</template>

<script>
import Breadcrumb from './components/Breadcrumb.vue';
import Navbar from "./components/Navbar.vue";
import Galley from "./components/Galley.vue";
import Slider from "./components/Slider.vue";
import Footer from './components/Footer.vue';
import Copyright from './components/Copyright.vue';

export default {
  name: 'App',
  components: {
    Navbar,
    Breadcrumb,
    Galley,
    Slider,
    Footer,
    Copyright
  }
}
</script>

<style>

</style>
