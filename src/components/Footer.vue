<template>
  <footer class="footer bg--green-dark">
    <div class="w-90 d-flex bg--whites py-20 py-lg-70 footer__banner">
      <div class="w-15"></div>
      <div>
        <h2 class="text--green text--bold text--35 text--sm-40 text--lg-60 lh--55 lh--lg-74 mb-40 mb-lg-50">Let’s make something<br>amazing together.</h2>
        <a href="" class="link text--uppercase text--gray">
          Let’s get started
        </a>
      </div>
    </div>
    <div class="container">
      <div class="d-flex w-100">
        <div class="w-33 w-md-20 mb-30 mb-lg-55 mb-lg-55">
          <h3 class="lh-40 text--whites mb-8 text--10 text--lg-16 text--green-light">Phone</h3>
          <a href='tel:+3250312832' class="d-block link lh-40 text--bold text--whites text--10 text--lg-16 footer__no-wrapp">+32 50 31 28 32</a>
        </div>
        <div class="mb-30 mb-lg-55">
          <h3 class="lh-40 text--whites text--10 text--lg-16 mb-8 text--green-light">Address</h3>
          <address class="lh-40  text--bold text--10 text--lg-16 text--whites">491 Merlin Crest Suite 963</address>
        </div>
      </div>
      <div class="d-md-flex py-20 py-sm-40 py-lg-60 w-100 footer__border">
        <div class="d-flex w-100 w-md-65">
          <div class="w-33 pr-15 w-md-30">
            <h3 class="lh-38 text--uppercase text--10 text--lg-16 text--whites mb-15 mb-lg-20">Services</h3>
            <a href="#" class="link d-block mb-10 mb-lg-15 text--green-light text--10 text--lg-16 lh-40 ">Brand Strategy</a>
            <a href="#" class="link d-block mb-10 mb-lg-15 text--green-light text--10 text--lg-16 lh-40">Product Design</a>
            <a href="#" class="link d-block mb-10 mb-lg-15 text--green-light text--10 text--lg-16 lh-40">Content Strategy</a>
            <a href="#" class="link d-block mb-10 mb-lg-15 text--green-light text--10 text--lg-16 lh-40">Brand Strategy</a>
            <a href="#" class="link d-block mb-10 mb-lg-15 text--green-light text--10 text--lg-16 lh-40">Development</a>
          </div>
          <div class="w-33 pr-15 w-md-40">
            <h3 class="lh-38 text--uppercase text--10 text--lg-16 text--whites mb-15 mb-lg-20 footer__no-wrapp">Help And Advice</h3>
            <a href="#" class="link d-block mb-10 mb-lg-15 text--green-light text--10 text--lg-16 lh-40">How it works</a>
            <a href="#" class="link d-block mb-10 mb-lg-15 text--green-light text--10 text--lg-16 lh-40">Contact Support</a>
            <a href="#" class="link d-block mb-10 mb-lg-15 text--green-light text--10 text--lg-16 lh-40">Privacy Policy</a>
            <a href="#" class="link d-block mb-10 mb-lg-15 text--green-light text--10 text--lg-16 lh-40 ">FAQ</a>
          </div>
          <div class="w-33 w-md-30 pr-15 footer__border--y">
            <h3 class="lh-38 text--uppercase text--10 text--lg-16 text--whites mb-15 mb-lg-20">Company</h3>
            <a href="#" class="link d-block mb-10 mb-lg-15 text--green-light text--10 text--lg-16 lh-40">About</a>
            <a href="#" class="link d-block mb-10 mb-lg-15 text--green-light text--10 text--lg-16 lh-40">Blog</a>
            <a href="#" class="link d-block mb-10 mb-lg-15 text--green-light text--10 text--lg-16 lh-40">Contact</a>
            <a href="#" class="link d-block mb-10 mb-lg-15 text--green-light text--10 text--lg-16 lh-40 ">Jobs</a>
          </div>
        </div>
        <div class="w-55 w-md-35 d-inline-block">
          <div class="pt-40 px-md-30 pt-md-0">
          <h3 class="lh-38 text--uppercase text--10 text--lg-16 text--whites mb-15 mb-lg-20">Get in Touch</h3>
          <p class="lh-40 text--10 text--lg-16 text--green-light mb-15 mb-lg-20">Feel free to get in touch with us vai email</p>
          <a href = "mailto: info.webovio@gmail.com" class="link text--10 text--sm-18 text--lg-24 text--bold lh-38 ">info.webovio@gmail.com</a>
          <div class="w-70  pt-5 pt-sm-15 pt-md-25">
            <a href="#" class="link link__soc h-10 w-10 mr-10"><img :src="require('@/assets/images/fb.svg')" class="h-90 w-90"></a>
            <a href="#" class="link link__soc h-10 w-10 mr-10"><img :src="require('@/assets/images/twitter.svg')" class="h-90 w-90"></a>
            <a href="#" class="link link__soc h-10 w-10 mr-10"><img :src="require('@/assets/images/google.svg')" class="h-90 w-90"></a>
            <a href="#" class="link link__soc h-10 w-10"><img :src="require('@/assets/images/im.svg')" class="h-90 w-90"></a>
          </div>
          </div>
        </div>
      </div>
      <div class="d-flex w-100 align-items-center">
        <div class="w-40 w-md-60 w-lg-65 py-18 py-lg-25">
          <a href="#" class="link d-flex">
            <img
              :src="require('@/assets/images/logo.png')"
              alt=""
              class="footer__logo"
            />
            <span class="text--whites text--14 text--md-21 text--lg-24 lh--14 lh--md-21 lh--lg-25">webovio<span class="text--yellow text--36">.</span></span>
          </a>
        </div>
        <div class="w-60 w-md-40 w-lg-35 lh-40 text--whites text--10 text--lg-16 text--green-light"><p class=" mb-0">© 2020@webovio. All Rights Reserved.</p></div>
      </div>
    </div>
  </footer>
</template>
