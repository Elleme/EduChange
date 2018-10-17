<template>
  <div id="Com-countdown-area">
    <div class="countdown-area bg-1 ptb-110 bg-opacity bg-relative">
      <div class="container">
        <div class="row">
          <div class="col-md-7 col-sm-7 col-xs-12 text-center">
            <div class="countdown-all">
              <h3>Get 100 of online courses for free </h3>
              <h1>Register Now</h1>
              <div class="timer">
                <div data-countdown="2019/01/01"></div>
              </div>
            </div>
          </div>
          <div class="col-md-5 col-sm-5 col-xs-12">
            <div class="register-from">
              <h3>Fil The Register Form</h3>
              <p>Lorem ipsum dolor sit amet, consectetur adipisicng elit, sed do eiusmod tempor </p>
              <form class="ordering">
                <input required="" placeholder="Your Name*" type="text">
                <input class="form-control2" required="" placeholder="Email Address*" type="email">
                <div class="orderby-wrapper">
                  <select name="orderby" class="orderby">
                    <option value="menu_order">Courses*</option>
                    <option value="popularity" selected='selected'>HS Diploma</option>
                    <option value="rating">Associate Degree</option>
                    <option value="date">Bachelor's Degree</option>
                    <option value="price">Master's Degree</option>
                    <option value="price-desc">Doctorate/Prof Degree</option>
                  </select>
                </div>
                <div class="sent text-center">
                  <button class="submit" type="submit">
                    submit
                  </button>
                </div>
              </form>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'CountdownArea',
    data () {
      return {
      }
    }
  }
</script>
