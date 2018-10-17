<template>
  <div id="Com-header-area">
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
                  <p>关注我们 :</p>
                  <ul>
                    <li><a href="#"><i class="icofont icofont-social-qq"></i></a></li>
                    <li><a href="#"><i class="icofont icofont-social-wechat"></i></a></li>
                    <li><a href="#"><i class="icofont icofont-social-weibo"></i></a></li>
                  </ul>
                </div>
                <div class="header-top-language f-left">
                  <ul>
                    <li><a href="#" data-toggle="dropdown">中文<i class="icofont icofont-simple-down"></i></a>
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
                <a href="/"><img height="80px" src="static/images/logo/eduLogo.jpg" alt=""> </a>
              </div>
            </div>
            <div class="col-md-8 hidden-sm hidden-xs">
              <div class="menu-area f-right">
                <nav>
                  <ul>
                    <li><a href="/">主页</a></li>
                    <li><a href="about.html">组织构成</a></li>
                    <li><a href="blog.html">精彩活动</a></li>
                    <li><a href="service.html">历史回顾</a></li>
                    <li><a href="page.html">关于教改</a></li>
                    <li><a href="contact.html">联系我们</a></li>
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

<style>
  .logo {
    padding-top: 10px !important;
  }

  .navy-bg {
    background: #b52726;
  }

</style>
