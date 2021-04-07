<template>
  <footer class="footer bg--green-dark">
    <div class="container">
      <div class="w-100 bg--whites py-20 py-lg-70 footer__banner">
        <h2
          class="w-100 w-md-75 text--green text--bold text--35 text--sm-40 text--md-50 text--lg-60 lh--55 lh--md-60 lh--lg-74 mb-20 mb-sm-40 mb-lg-50"
        >
          Let’s make something amazing together.
        </h2>
        <a href="#" class="link text--uppercase link--yellow">
          Let’s get started
        </a>
      </div>
    </div>
    <div class="container">
      <div class="d-flex flex-wrap w-100">
        <div class="w-100 w-sm-40 w-lg-19 mb-30 mb-lg-55 mb-lg-55">
          <h3 class="footer__text">
            Phone
          </h3>
          <a
            href="tel:+3250312832"
            class="link footer__connect footer__no-wrapp"
            >+32 50 31 28 32</a
          >
        </div>
        <div class="w-100 w-sm-60 w-lg-80 mb-30 mb-lg-55">
          <h3 class="footer__text">
            Address
          </h3>
          <address class="link footer__connect">
            491 Merlin Crest Suite 963
          </address>
        </div>
      </div>
      <div
        class="d-flex flex-wrap py-20 py-sm-40 py-lg-60 w-100 footer__border"
      >
        <div class="w-100 w-sm-40 pb-50 pb-lg-0 pr-15 w-lg-19">
          <h3
            class="lh-38 text--uppercase text--14 text--lg-16 text--whites mb-15 mb-lg-20"
          >
            Services
          </h3>
          <a
            :href="servisesLink.url"
            v-for="servisesLink in servisesLinks"
            :key="servisesLink.id"
            class="link footer__text d-block"
            >{{ servisesLink.name }}</a
          >
        </div>
        <div class="w-100 w-sm-60 pb-50 pb-lg-0 pr-15 w-lg-22">
          <h3
            class="lh-38 text--uppercase text--14 text--lg-16 text--whites mb-15 mb-lg-20 footer__no-wrapp"
          >
            Help And Advice
          </h3>
          <a
            :href="adviceLink.url"
            v-for="adviceLink in adviceLinks"
            :key="adviceLink.id"
            class="link footer__text d-block"
            >{{ adviceLink.name }}</a
          >
        </div>
        <div
          class="mb-30 mb-sm-0 w-100 w-sm-40 w-lg-19 pr-15 footer__border--y"
        >
          <h3
            class="lh-38 text--uppercase text--14 text--lg-16 text--whites mb-15 mb-lg-20"
          >
            Company
          </h3>
          <a
            :href="companyLink.url"
            v-for="companyLink in companyLinks"
            :key="companyLink.id"
            class="link footer__text d-block"
            >{{ companyLink.name }}</a
          >
        </div>
        <div class="w-100 w-sm-60 w-lg-39 ">
          <div class="pl-lg-80 pl-xl-110 d-inline-block">
            <h3
              class="lh-38 text--uppercase text--14 text--lg-16 text--whites mb-15 mb-lg-23"
            >
              Get in Touch
            </h3>
            <p
              class="text--14 lh--lg-26  text--lg-16 text--green-light mb-15 mb-lg-20"
            >
              Feel free to get in touch with us vai email
            </p>
            <a
              href="mailto: info.webovio@gmail.com"
              class="link text--14 text--sm-18 text--lg-20 text--xl-24 text--bold lh-38"
              >info.webovio@gmail.com</a
            >
            <div class="w-40 w-sm-55 d-flex justify-content-between pt-25">
              <a
                :href="icon.url"
                class="link link__soc"
                v-for="icon in icons"
                :key="icon.id"
                ><img :src="icon.imgSrc" class="footer__icon"
              /></a>
            </div>
          </div>
        </div>
      </div>
      <div class="d-flex flex-wrap w-100 align-items-center">
        <div class="w-100 w-sm-40 w-md-60 w-lg-65 py-18 py-lg-25">
          <a href="#" class="link ">
            <img
              :src="require('@/assets/images/logo.png')"
              alt=""
              class="footer__logo"
            />
            <span
              class="text--whites text--14 text--md-21 text--lg-24 lh--14 lh--md-21 lh--lg-25"
              >webovio<span class="text--yellow text--36">.</span></span
            >
          </a>
        </div>
        <div
          class="w-100 w-sm-60 w-md-40 w-lg-35 lh-40 text--whites text--10 text--lg-16 text--green-light"
        >
          <p class="mb-10 mb-sm-0">© 2020@webovio. All Rights Reserved.</p>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  data() {
    return {
      servisesLinks: [
        {
          name: 'Brand Strategy',
          url: '#1'
        },
        {
          name: 'Product Design',
          url: '#2'
        },
        {
          name: 'Content Strateg',
          url: '#3'
        },
        {
          name: 'Brand Strategy',
          url: '#3'
        },
        {
          name: 'Development',
          url: '#4'
        }
      ],
      adviceLinks: [
        {
          name: 'How it works',
          url: '#adviceLink1'
        },
        {
          name: 'Contact Support',
          url: '#adviceLink2'
        },
        {
          name: 'Privacy Policy',
          url: '#adviceLink3'
        },
        {
          name: 'FAQ',
          url: '#adviceLink4'
        }
      ],
      companyLinks: [
        {
          name: 'About',
          url: '#contactLink1'
        },
        {
          name: 'Blog',
          url: '#contactLink2'
        },
        {
          name: 'Contact',
          url: '#contactLink3'
        },
        {
          name: 'Jobs',
          url: '#contactLink4'
        }
      ],
      icons: [
        {
          url: '#1',
          imgSrc: require('@/assets/images/fb.svg')
        },
        {
          url: '#2',
          imgSrc: require('@/assets/images/twitter.svg')
        },
        {
          url: '#3',
          imgSrc: require('@/assets/images/google.svg')
        },
        {
          url: '#4',
          imgSrc: require('@/assets/images/im.svg')
        }
      ]
    }
  }
}
</script>
