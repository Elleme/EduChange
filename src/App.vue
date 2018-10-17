<template>
  <div id="app">
    <!--<img src="./assets/logo.png">-->
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App',
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

<style>
/*#app {*/
  /*font-family: 'Avenir', Helvetica, Arial, sans-serif;*/
  /*-webkit-font-smoothing: antialiased;*/
  /*-moz-osx-font-smoothing: grayscale;*/
  /*text-align: center;*/
  /*color: #2c3e50;*/
  /*margin-top: 60px;*/
/*}*/
</style>
