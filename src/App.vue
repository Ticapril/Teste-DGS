<template>
  <div>
    <Header />
    <Banner />
    <AboutUs />
    <Products />
    <Footer />
  </div>
</template>

<script>
import Header from './components/Header.vue';
import Banner from './components/Banner.vue';
import Footer from './components/Footer.vue';
import AboutUs from './components/AboutUs.vue';
import Products from './components/Products.vue';

export default {
  name: 'App',
  components: { Header, Banner, Footer, AboutUs, Products },
}
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
