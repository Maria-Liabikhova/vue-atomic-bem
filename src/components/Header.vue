<template>
  <header class="header h-100">
    <div class="container header__relative">
      <div class="d-flex flex-column justify-content-between">
        <div
          class="d-flex justify-content-between pt-23 mb-30 mb-sm-40 mb-lg-80 mb-xl-121"
        >
          <a
            href="#"
            class="link d-flex align-items-start w-30 w-sm-25 w-lg-18"
          >
            <img
              :src="require('@/assets/images/logo.png')"
              alt="lable webovio"
              class="w-30 pr-3 pr-md-5 pr-lg-12"
            />
            <img
              :src="require('@/assets/images/webovio.svg')"
              alt="logo webovio"
              class="w-65"
            />
          </a>
          <Collapse />
        </div>
      </div>
      <main class="d-block w-100 w-md-65 w-lg-55">
        <p class="text--whites text--10 text--md-14 lh--21 mb-10 mb-sm-22 ">
          A place where
        </p>
        <h1
          class="text--center text--md-left text--24 text--sm-36 text--md-50 text--xl-60 text--whites text--bold mb-24 lh--sm-50 lh--md-65 lh--xl-74"
        >
          A creative agency for redemptive brands
        </h1>
        <h2
          class="text--whites text--10 text--sm-14 text--md-16 text--regular lh--sm-18 lh--md-26 mb-25 mb-md-45"
        >
          Anteelo is a leading strategic design firm that builds powerful
          digital solutions for startups and enterprises.
        </h2>
        <a
          href="#"
          class="link text--12 text--md-16 link--yellow link--arrow mb-40 mb-sm-60 mb-md-107 lh--md-24"
          >Get in touch</a
        >
      </main>
      <nav class="header__brands d-flex align-items-center">
        <div
          class="w-100 d-flex flex-wrap align-items-center justify-content-center justify-content-md-between"
        >
          <a
            v-for="logo in logos"
            :key="logo.id"
            :href="logo.url"
            class="link w-50 w-md-20 pl-20 pl-md-30 pl-lg-50 pl-xl-65 pr-10"
          >
            <img :src="logo.imgSrc" class="w-50 w-md-100" alt="brand logo" />
          </a>
        </div>
      </nav>
    </div>
  </header>
</template>

<script>
import Collapse from '@/components/Collapse'
export default {
  components: { Collapse: Collapse },
  data() {
    return {
      logos: [
        {
          url: '#1',
          imgSrc: require('@/assets/images/brand-1.png')
        },
        {
          url: '#2',
          imgSrc: require('@/assets/images/brand-2.png')
        },
        {
          url: '#3',
          imgSrc: require('@/assets/images/brand-5.png')
        },
        {
          url: '#4',
          imgSrc: require('@/assets/images/brand-4.png')
        },
        {
          url: '#5',
          imgSrc: require('@/assets/images/brand-3.png')
        }
      ]
    }
  }
}
</script>
