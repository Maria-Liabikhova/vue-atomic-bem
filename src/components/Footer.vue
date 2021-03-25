<template>
  <div class="footer pt-322 bg--green-dark">
    <div class="container">
      <div class="d-flex w-100 pt-120">
        <div class=" w-20 mb-55">
          <h6 class="lh-40 text--whites mb-8 text--green-light">Phone</h6>
          <a href='tel:+3250312832' class=" link w-20 lh-40 text--bold text--whites footer__no-wrapp">+32 50 31 28 32</a>
        </div>
        <div class="w-20 mb-55">
          <h6 class="lh-40 text--whites mb-8 text--green-light">Address</h6>
          <address class="lh-40  text--bold text--whites">491 Merlin Crest Suite 963</address>
        </div>
      </div>
      <div class="d-flex py-60 w-100 footer__border">
        <div class="w-20 d-flex flex-column">
          <h6 class="lh-38 text--uppercase text--16 text--whites mb-20">Services</h6>
          <a href="#" class="link mb-15 text--green-light lh-40 ">Brand Strategy</a>
          <a href="#" class="link mb-15 text--green-light lh-40">Product Design</a>
          <a href="#" class="link mb-15 text--green-light lh-40">Content Strategy</a>
          <a href="#" class="link mb-15 text--green-light lh-40">Brand Strategy</a>
          <a href="#" class="link mb-15 text--green-light lh-40">Development</a>
        </div>
        <div class="w-25 d-flex flex-column">
          <h6 class="lh-38 text--uppercase text--16 text--whites mb-20 footer__no-wrapp">Help And Advice</h6>
          <a href="#" class="link mb-15 text--green-light lh-40">How it works</a>
          <a href="#" class="link mb-15 text--green-light lh-40">Contact Support</a>
          <a href="#" class="link mb-15 text--green-light lh-40">Privacy Policy</a>
          <a href="#" class="link mb-15 text--green-light lh-40 ">FAQ</a>
        </div>
        <div class="w-20 d-flex flex-column footer__border--y">
          <h6 class="lh-38 text--uppercase text--16 text--whites mb-20">Company</h6>
          <a href="#" class="link mb-15 text--green-light lh-40">About</a>
          <a href="#" class="link mb-15 text--green-light lh-40">Blog</a>
          <a href="#" class="link mb-15 text--green-light lh-40">Contact</a>
          <a href="#" class="link mb-15 text--green-light lh-40 ">Jobs</a>
        </div>
        <div class="w-35 d-flex flex-column">
          <div class="px-30">
          <p class="lh-38 text--uppercase text--16 text--whites mb-20">Get in Touch</p>
          <p class="lh-40 text--whites text--green-light mb-20">Feel free to get in touch with us vai email</p>
          <a href = "mailto: info.webovio@gmail.com" class="link text--24 text--bold lh-38 ">info.webovio@gmail.com</a>
          <div class="w-70 pt-25">
            <a href="#" class="link link__soc h-10 w-10 mr-10"><img :src="require('@/assets/images/fb.svg')" class="h-90 w-90"></a>
            <a href="#" class="link link__soc h-10 w-10 mr-10"><img :src="require('@/assets/images/twitter.svg')" class="h-90 w-90"></a>
            <a href="#" class="link link__soc h-10 w-10 mr-10"><img :src="require('@/assets/images/google.svg')" class="h-90 w-90"></a>
            <a href="#" class="link link__soc h-10 w-10"><img :src="require('@/assets/images/im.svg')" class="h-90 w-90"></a>
          </div>
          </div>
        </div>
      </div>
      <div class="d-flex w-100 align-items-center">
        <div class="w-65 pt-25 pb-25 ">
          <a href="#" class="link link--logo d-flex ">
            <img
              :src="require('@/assets/images/logo.png')"
              alt=""
              class="footer__logo"
            />
            <span class="text--whites text--24 lh--25">webovio<span class="text--yellow text--36">.</span></span>
          </a>
        </div>
        <div class="d-flex">
          <div class="lh-40 text--whites text--green-light">© 2020@webovio. All Rights Reserved.</div>
        </div>
      </div>
    </div>
  </div>
</template>
