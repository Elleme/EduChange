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
      <service-area></service-area>
      <banner-blog-area></banner-blog-area>
      <countdown-area></countdown-area>
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
      <style-customizer></style-customizer>
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

      js1.src = 'static/js/vendor/modernizr-2.8.3.min.js';
      js2.src = 'static/js/vendor/jquery-1.12.0.min.js';
      js3.src = 'static/js/bootstrap.min.js';
      js4.src = 'static/js/ajax-mail.js';
      js5.src = 'static/js/plugins.js';
      js6.src = 'static/js/main.js';
      document.body.appendChild(js1);
      document.body.appendChild(js2);
      document.body.appendChild(js3);
      document.body.appendChild(js4);
      document.body.appendChild(js5);
      document.body.appendChild(js6);
    },
  }
</script>



