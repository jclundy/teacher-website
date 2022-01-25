<template>
  <div id="app">

    <PreLoader />
    <HomeCover />
    <Navigation/>
    <AboutMe/>
    <Resume/>
    <Uwaft/> 
    <Footer/>

    <div class="scroll-up">
      <a href="#home"><i class="fa fa-angle-up"></i></a>
    </div>
  </div>
</template>

<script>
// import PreLoader from "./sections/PreLoader.vue";
import HomeCover from "./sections/HomeCover.vue";
import Navigation from "./sections/Navigation.vue";
import AboutMe from "./sections/AboutMe.vue";
import Resume from "./sections/Resume.vue";
import Footer from "./sections/Footer.vue";
import Uwaft from "./sections/Uwaft.vue";

export default {
  name: "App",
  components: {
    // PreLoader,
    HomeCover,
    Navigation,
    AboutMe,
    Resume,
    Uwaft,
    Footer,
  },
};
</script>

<style>
@import "./assets/bootstrap/css/bootstrap.min.css";
@import "./assets/css/style.css";
@import "./assets/css/responsive.css";
@import "./assets/css/magnific-popup.css";
@import "./assets/css/animate.css";
@import "./assets/css/font-awesome.min.css";

.align-center {
  text-align: center;
}

</style>
