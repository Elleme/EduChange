<template>
  <div>
    <header class="header-area">
      <div class="header-top navy-bg ptb-20">
        <div class="container">
          <div class="row">
            <div class="col-md-6 col-sm-6 col-xs-12">
              <div class="header-top-info">
                <ul>
                  <li>
                    <a href="#">
                      <i class="icofont icofont-ui-call"></i>
                      电话  (+86) 13055644369
                    </a>
                  </li>
                  <li>
                    <a href="#">
                      <i class="icofont icofont-envelope"></i>
                      895254752@qq.com
                    </a>
                  </li>
                </ul>
              </div>
            </div>
            <div class="col-md-6 col-sm-6 hidden-xs">
              <div class="header-top-right f-right">
                <div class="header-top-social f-right">
                  <p>Follow Us :</p>
                  <ul>
                    <li><a href="#"><i class="icofont icofont-social-facebook"></i></a></li>
                    <li><a href="#"><i class="icofont icofont-social-twitter"></i></a></li>
                    <li><a href="#"><i class="icofont icofont-social-github"></i></a></li>
                  </ul>
                </div>
                <div class="header-top-language f-left">
                  <ul>
                    <li><a href="#" data-toggle="dropdown">English<i class="icofont icofont-simple-down"></i></a>
                      <ul class="dropdown-menu">
                        <li><a href="#">English</a></li>
                        <li><a href="#">English</a></li>
                        <li><a href="#">English</a></li>
                      </ul>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="header-bottom stick-h2">
        <div class="container">
          <div class="row">
            <div class="col-md-4 col-sm-12 col-xs-12">
              <div class="logo">
                <a href="index.html"><img src="static/images/logo/logo.png" alt=""> </a>
              </div>
            </div>
            <div class="col-md-8 hidden-sm hidden-xs">
              <div class="menu-area f-right">
                <nav>
                  <ul>
                    <li><a href="index.html">HOME</a></li>
                    <li><a href="about.html">ABOUT</a></li>
                    <li><a href="blog.html">BLOG</a></li>
                    <li><a href="service.html">SERVICE</a></li>
                    <li><a href="page.html">PAGE</a></li>
                    <li><a href="contact.html">CONTACT</a></li>
                  </ul>
                </nav>
              </div>
            </div>
          </div>
        </div>
      </div>
    </header>
  </div>
</template>

<script>
  export default {
    name: 'HeaderArea',
    data () {
      return {
      }
    }
  }
</script>
