
<template>
  <div id="app">
    <!-- <div id="page-loader" class="bg-white">
    <svg class="loader" width="32px" height="32px" viewBox="0 0 32 32" xmlns="http://www.w3.org/2000/svg"><circle class="circle" fill="none" stroke-width="2" stroke-linecap="round" cx="16" cy="16" r="14"></circle></svg>
    <span class="loading-txt text-muted">Loading...</span>
  </div> -->
<!-- Loader / End -->

<!-- Header -->
<header id="header" class="dark">
    <a href="index.html" class="logo">
        <h3 style="font-family: 'Exo', sans-serif;"># JNKSOLUTIONS</h3>
    </a>

    <!-- Navigation -->
    <nav id="main-menu">
        <div class="nav-wrapper">
            <ul class="nav nav-primary">
                <li><a href="index.html" class="active"><i class="li-home"></i>Start</a></li>
                <li><a href="about.html"><i class="li-feedback"></i>About</a></li>
                <li><a href="services.html"><i class="li-laptop"></i>Services</a></li>
                <li><a href="portfolio-3-cols.html"><i class="li-imac"></i>Portfolio</a></li>
                <li><a href="blog-sidebar-right.html"><i class="li-pen"></i>Blog</a></li>
                <li><a href="contact.html"><i class="li-email"></i>Contact</a></li>
            </ul>
        </div>
        <span class="selector"></span>
    </nav>

</header>
<!-- Header / End -->

<!-- Content -->
    <router-view/>
    <footer id="footer" class="border-top">
    <div class="container-fluid container-custom">
        <div class="row">
            <div class="col-xl-5 text-xl-left text-xs-center">
                <div class="module-group">
                    <div class="module copyright">
                        <a href="index.html" class="logo mr-15"><img src="assets/img/logo-dark.svg" height="80" alt=""></a>
                        <span class="text-muted">Copyright Skill 2018 © <a href="http://www.jnksolutions.in/" target="blank">JNKSOLUTIONS</a>.</span>
                    </div>
                </div>
            </div>
            <div class="col-xl-7 text-xl-right text-xs-center">
                <div class="module-group">
                    <div class="module">
                        <span class="text-muted mr-5">Language:</span>
                        <ul class="nav-footer">
                            <li class="active"><a href="#">English</a></li>
                        </ul>
                    </div>
                    <div class="module">
                        <span class="text-muted mr-10">Follow Us</span>
                        <a href="#" class="icon icon-circle icon-hover icon-secondary icon-sm"><i class="ti-facebook"></i></a>
                        <a href="#" class="icon icon-circle icon-hover icon-secondary icon-sm"><i class="ti-twitter-alt"></i></a>
                        <a href="#" class="icon icon-circle icon-hover icon-secondary icon-sm"><i class="ti-google"></i></a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</footer>
<!-- Footer / End -->
  </div>
</template>

<script>
import "./assets/js/isotope.pkgd.js"
import "./assets/js/plugins.js"




export default {
  name: 'App',
  resolve: {

    alias: {
      'masonry': 'masonry-layout',
      'isotope': 'isotope-layout'
    }
  }
}
</script>

<style>
</style>
