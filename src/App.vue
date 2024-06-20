<template>
    <div id="app">
    <div class="container-fluid p-0">
      <div class="row m-0 header">
        <div class="col p-0">
          <Header />
        </div>
      </div>
      <div class="row m-0">
        <div class="col p-0">
          <Banner />
        </div>
      </div>
      <div class="row m-0" id="Profile">
        <div class="col p-0">
          <Profilo />
        </div>
      </div>
      <!-- <div class="row m-0">
        <div class="col p-0">
          <ContactUs />
        </div>
      </div> -->
      <!-- <div class="row m-0">
        <div class="col p-0">
          <Home />
        </div>
      </div> -->
      <BackToTop />
      <div class="row m-0" id="Footer">
        <div class="col p-0">
          <Footer />
        </div>
      </div>
    </div>
  </div>
  
</template>

<script>
import Header from './components/Header.vue';
import Banner from './components/Banner.vue';
import Home from './components/Home.vue';
import Footer from './components/Footer.vue';
import Profilo from './components/Profilo.vue';
import BackToTop from './components/BackToTop.vue';
// import ContactUs from './components/ContactUs.vue';


export default {
  name: 'App',
  components: {
    Header,
    Banner,
    Home,
    Footer,
    Profilo,
    BackToTop,
  },
};
</script>

<style>
  @media screen and (max-width: 768px) {
    .header{
      position: sticky;
      top: 0;
      z-index: 99999;
    }
  }
  
</style>
