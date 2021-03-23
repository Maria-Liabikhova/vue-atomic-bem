<template>
  <div class="footer pt-322 bg--green-dark">
    <div class="container">
      <div class="d-flex w-100 pt-120">
        <section class="w-20 d-flex flex-column mb-55">
          <p class="lh-40 text--whites mb-8 text--green-light">Phone</p>
          <p class="w-20 lh-40 text--bold text--whites footer__no-wrapp">+32 50 31 28 32</p>
        </section>
        <section class="w-20 d-flex flex-column mb-55">
          <p class="lh-40 text--whites mb-8 text--green-light">Address</p>
          <p class="lh-40  text--bold text--whites">491 Merlin Crest Suite 963</p>
        </section>
        <section class="w-60 d-flex flex-column mb-55"></section>
      </div>
      <div class="d-flex py-60 w-100 footer__border">
        <section class="w-20 d-flex flex-column">
          <p class="w-20 lh-38 text--uppercase text--bold text--whites mb-20">Services</p>
          <a href="#" class="link mb-15 text--green-light lh-40 ">Brand Strategy</a>
          <a href="#" class="link mb-15 text--green-light lh-40">Product Design</a>
          <a href="#" class="link mb-15 text--green-light lh-40">Content Strategy</a>
          <a href="#" class="link mb-15 text--green-light lh-40">Brand Strategy</a>
          <a href="#" class="link mb-15 text--green-light lh-40">Development</a>
        </section>
        <section class="w-25 d-flex flex-column">
          <p class="lh-38 pr-120 text--bold text--uppercase text--whites footer__no-wrapp mb-20">Help And Advice</p>
          <a href="#" class="link mb-15 text--green-light lh-40">How it works</a>
          <a href="#" class="link mb-15 text--green-light lh-40">Contact Support</a>
          <a href="#" class="link mb-15 text--green-light lh-40">Privacy Policy</a>
          <a href="#" class="link mb-15 text--green-light lh-40 ">FAQ</a>
        </section>
        <section class="w-20 d-flex flex-column footer__border--y">
          <p class=" w-20 mr-124 lh-38 text--uppercase text--bold text--whites footer__company  mb-20">Company</p>
          <a href="#" class="link mb-15 text--green-light lh-40">About</a>
          <a href="#" class="link mb-15 text--green-light lh-40">Blog</a>
          <a href="#" class="link mb-15 text--green-light lh-40">Contact</a>
          <a href="#" class="link mb-15 text--green-light lh-40 ">Jobs</a>
        </section>
        <section class="w-35 d-flex flex-column">
          <div class="px-30">
          <p class=" lh-38 text--uppercase text--bold text--whites mb-20">Get in Touch</p>
          <p class="lh-40 text--whites text--green-light mb-20">Feel free to get in touch with us vai email</p>
          <a href="#" class="link text--24 text--bold lh-38 ">info.webovio@gmail.com</a>
          <div class="d-flex w-70 pt-25">
            <!-- <a href="#" class="link "><img :src="require('@/assets/images/fb.svg')" class="h-100 w-100"></a>
            <a href="#" class="link dk "><img :src="require('@/assets/images/twitter.svg')" class="h-85 w-85"></a>
            <a href="#" class="link "><img :src="require('@/assets/images/google.svg')" class="h-100 w-100"></a>
            <a href="#" class="link d-flex footer__align "><img :src="require('@/assets/images/im.svg')" class="h-60 w-60"></a> -->
            <img :src="require('@/assets/images/fb.svg')" class="h-15 w-15 pr-5">
            <img :src="require('@/assets/images/twitter.svg')" class="h-15 w-15 pr-5">
            <img :src="require('@/assets/images/google.svg')" class="h-15 w-15 pr-5">
            <img :src="require('@/assets/images/im.svg')" class="h-15 w-15">
          </div>
          </div>
        </section>
      </div>
      <div class="d-flex w-100 align-items-center">
        <section class="w-65 pt-25 pb-25 ">
          <a href="#" class="link link--logo d-flex ">
            <img
              :src="require('@/assets/images/logo.png')"
              alt=""
              class="footer__logo"
            />
            <span class="text--whites text--24 lh--25">webovio<span class="text--yellow text--36">.</span></span>
          </a>
        </section>
        <section class="d-flex">
          <div class="lh-40 text--whites text--green-light">© 2020@webovio. All Rights Reserved.</div>
        </section>
      </div>
    </div>
  </div>
</template>
