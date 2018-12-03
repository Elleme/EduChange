<template>
  <div id="EduHomepage">
    <!--[if lt IE 8]>
    <p class="browserupgrade">You are using an <strong>outdated</strong> browser. Please <a href="http://browsehappy.com/">upgrade your browser</a> to improve your experience.</p>
    <![endif]-->
    <!-- Body main wrapper start -->
    <div class="wrapper">
      <!-- Start of header area -->
      <header-area></header-area>
      <!-- mobile-menu-area start -->
      <mobile-menu-area></mobile-menu-area>
      <!-- mobile-menu-area end -->
      <!-- End of header area -->
      <!-- Start of slider area -->
      <slider-area></slider-area>
      <!-- End of slider area -->
      <!-- Start page content -->
      <!--<service-area></service-area>-->
      <!--<banner-blog-area></banner-blog-area>-->
      <!--<countdown-area></countdown-area>-->
      <event-area></event-area>
      <counter-area></counter-area>
      <testimonial-area></testimonial-area>
      <!-- End page content -->
      <!-- Start footer area -->
      <footer-area></footer-area>
      <!-- End footer area -->
      <!-- start scrollUp
      ============================================ -->
      <div id="toTop">
        <i class="fa fa-chevron-up"></i>
      </div>
      <!--style-customizer start -->
      <!--<style-customizer></style-customizer>-->
      <div class="style-customizer closed">
        <div class="buy-button">
          <a href="index.html" class="customizer-logo"><img src="static/images/logo/logo.png" alt="Theme Logo"></a>
          <a class="opener" href="#"><i class="fa fa-cog fa-spin"></i></a> <a class="button button-border" href="#">Buy now!</a>
        </div>
        <div class="clearfix content-chooser">
          <h3>Layout Options</h3>
          <p>Which layout option you want to use?</p>
          <ul class="layoutstyle clearfix">
            <li class="wide-layout selected" data-style="wide" title="wide"> Wide </li>
            <li class="boxed-layout" data-style="boxed" title="boxed"> Boxed </li>
          </ul>
          <h3>Color Schemes</h3>
          <p>Which theme color you want to use? Select from here.</p>
          <ul class="styleChange clearfix">
            <li class="color-1 selected" title="color-1" data-style="color-1" ></li>
            <li class="color-2" title="color-2" data-style="color-2"></li>
            <li class="color-3" title="color-3" data-style="color-3"></li>
            <li class="color-4" title="color-4" data-style="color-4"></li>
            <li class="color-5" title="color-5" data-style="color-5"></li>
            <li class="color-6" title="color-6" data-style="color-6"></li>
            <li class="color-7" title="color-7" data-style="color-7"></li>
            <li class="color-8" title="color-8" data-style="color-8"></li>
            <li class="color-9" title="color-9" data-style="color-9"></li>
            <li class="color-10" title="color-10" data-style="color-10"></li>
            <li class="color-11" title="color-11" data-style="color-11"></li>
            <li class="color-12" title="color-12" data-style="color-12"></li>
            <li class="color-13" title="color-13" data-style="color-13"></li>
            <li class="color-14" title="color-14" data-style="color-14"></li>
            <li class="color-15" title="color-15" data-style="color-15"></li>
            <li class="color-16" title="color-16" data-style="color-16"></li>
            <li class="color-17" title="color-17" data-style="color-17"></li>
            <li class="color-18" title="color-18" data-style="color-18"></li>
            <li class="color-19" title="color-19" data-style="color-19"></li>
            <li class="color-20" title="color-20" data-style="color-20"></li>
          </ul>
          <h3>Background Patterns</h3>
          <p>Which background pattern you want to use?</p>
          <ul class="patternChange clearfix">
            <li class="pattern-1" data-style="pattern-1" title="pattern-1"></li>
            <li class="pattern-2" data-style="pattern-2" title="pattern-2"></li>
            <li class="pattern-3" data-style="pattern-3" title="pattern-3"></li>
            <li class="pattern-4" data-style="pattern-4" title="pattern-4"></li>
            <li class="pattern-5" data-style="pattern-5" title="pattern-5"></li>
            <li class="pattern-6" data-style="pattern-6" title="pattern-6"></li>
            <li class="pattern-7" data-style="pattern-7" title="pattern-7"></li>
            <li class="pattern-8" data-style="pattern-8" title="pattern-8"></li>
          </ul>
          <h3>Background Images</h3>
          <p>Which background image you want to use?</p>
          <ul class="patternChange main-bg-change clearfix">
            <li class="main-bg-1" data-style="main-bg-1" title="Background 1"> <img src="static/images/customizer/bodybg/01.jpg" alt=""></li>
            <li class="main-bg-2" data-style="main-bg-2" title="Background 2"> <img src="static/images/customizer/bodybg/02.jpg" alt=""></li>
            <li class="main-bg-3" data-style="main-bg-3" title="Background 3"> <img src="static/images/customizer/bodybg/03.jpg" alt=""></li>
            <li class="main-bg-4" data-style="main-bg-4" title="Background 4"> <img src="static/images/customizer/bodybg/04.jpg" alt=""></li>
            <li class="main-bg-5" data-style="main-bg-5" title="Background 5"> <img src="static/images/customizer/bodybg/05.jpg" alt=""></li>
            <li class="main-bg-6" data-style="main-bg-6" title="Background 6"> <img src="static/images/customizer/bodybg/06.jpg" alt=""></li>
            <li class="main-bg-7" data-style="main-bg-7" title="Background 7"> <img src="static/images/customizer/bodybg/07.jpg" alt=""></li>
            <li class="main-bg-8" data-style="main-bg-8" title="Background 8"> <img src="static/images/customizer/bodybg/08.jpg" alt=""></li>
          </ul>
          <ul class="resetAll">
            <li><a class="button button-border button-reset" href="#">Reset All</a></li>
          </ul>
        </div>
      </div>
      <!--style-customizer end -->
    </div>
    <!-- Body main wrapper end -->
  </div>
</template>

<script>
  import HeaderArea from "../components/Header";
  import MobileMenuArea from "../components/MobileMenuArea";
  import SliderArea from "../components/SliderArea";
  import ServiceArea from "../components/ServiceArea";
  import BannerBlogArea from "../components/BannerBlogArea";
  import CountdownArea from "../components/CountdownArea";
  import EventArea from "../components/EventArea";
  import CounterArea from "../components/CounterArea";
  import TestimonialArea from "../components/TestimonialArea";
  import FooterArea from "../components/FooterArea";
  import StyleCustomizer from "../components/StyleCustomizer";

  export default {
    name: 'HomePage',
    components: {
      StyleCustomizer,
      FooterArea,
      TestimonialArea,
      CounterArea,
      EventArea, CountdownArea, BannerBlogArea, ServiceArea, SliderArea, MobileMenuArea, HeaderArea},
    data () {
      return {

      }
    },
    mounted() {

      const js1 = document.createElement('script');
      const js2 = document.createElement('script');
      const js3 = document.createElement('script');
      const js4 = document.createElement('script');
      const js5 = document.createElement('script');
      const js6 = document.createElement('script');

      js1.type = 'text/javascript';
      js2.type = 'text/javascript';
      js3.type = 'text/javascript';
      js4.type = 'text/javascript';
      js5.type = 'text/javascript';
      js6.type = 'text/javascript';

      js1.src = '../../static/js/vendor/modernizr-2.8.3.min.js';
      js2.src = '../../static/js/vendor/jquery-1.12.0.min.js';
      js3.src = '../../static/js/bootstrap.min.js';
      js4.src = '../../static/js/ajax-mail.js';
      js5.src = '../../static/js/plugins.js';
      js6.src = '../../static/js/main.js';
      document.body.appendChild(js1);
      document.body.appendChild(js2);
      document.body.appendChild(js3);
      document.body.appendChild(js4);
      document.body.appendChild(js5);
      document.body.appendChild(js6);
    },
  }
</script>



