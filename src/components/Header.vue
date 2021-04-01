<template>
  <header class="header h-100">
    <div class="container">
      <div class="d-flex flex-column justify-content-between">
        <div class="d-flex justify-content-between pt-23 mb-30 mb-sm-40 mb-lg-80 mb-xl-121">
          <a href="#" class="link d-flex align-items-start w-18">
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
          <nav class="nav header__top d-flex flex-wrap">
            <a
              href="#"
              class="link d-block text--10 text--sm-14 text--uppercase space--1 px-8"
              >link1</a
            >
            <a
              href="#"
              class="link d-block text--10 text--sm-14 text--uppercase space--1 px-8"
              >link2</a
            >
            <a
              href="#"
              class="link d-block text--10 text--sm-14 text--uppercase space--1 px-8"
              >link3</a
            >
            <a
              href="#"
              class="link d-block text--10 text--sm-14 text--uppercase space--1 px-8"
              >link4</a
            >
          </nav>
        </div>
      </div>
      <main class="d-block w-65 w-lg-55">
        <p class="text--whites text--10 text--md-14 lh--21 mb-10 mb-sm-22 ">A place where</p>
        <h1 class="text--24 text--sm-36 text--md-50 text--xl-60 text--whites text--bold mb-24 lh--sm-50 lh--md-65 lh--xl-74">
          A creative agency for redemptive brands
        </h1>
        <h2 class="text--whites text--10 text--sm-14 text--md-16 text--regular lh--sm-18 lh--md-26 mb-sm-25 mb-md-45">
          Anteelo is a leading strategic design firm that builds powerful
          digital solutions for startups and enterprises.
        </h2>
        <a href="#" class="link text--12 text--sm-16 link--yellow link--arrow mb-40 mb-sm-60 mb-md-107 lh--24">Get in touch</a>
      </main>
      <nav
        class="header__brands"
      ><div class="w-100 d-flex align-items-center justify-content-between">
        <a href="#" class="link w-20 pl-20 pl-md-30 pl-lg-50 pl-xl-65 pt-20 pt-md-30 pt-lg-55 pt-xl-60 pb-20 pb-md-30 pb-lg-50 pb-xl-54">
          <img :src="require('@/assets/images/brand-1.png')" class="w-100" alt="brand logo" />
        </a>
        <a href="#" class="link w-20 pl-20 pl-md-30 pl-lg-50 pl-xl-65 pt-20 pt-md-30 pt-lg-55 pt-xl-60 pb-20 pb-md-30 pb-lg-50 pb-xl-54">
          <img :src="require('@/assets/images/brand-2.png')" class="w-100" alt="brand logo" />
        </a>
        <a href="#" class="link w-20 pl-20 pl-md-30 pl-lg-50 pl-xl-65 pt-20 pt-md-30 pt-lg-55 pt-xl-60 pb-20 pb-md-30 pb-lg-50 pb-xl-54">
          <img :src="require('@/assets/images/brand-5.png')" class="w-100" alt="brand logo" />
        </a>
        <a href="#" class="link w-20 pl-20 pl-md-30 pl-lg-50 pl-xl-65 pt-20 pt-md-30 pt-lg-55 pt-xl-60 pb-20 pb-md-30 pb-lg-50 pb-xl-54">
          <img :src="require('@/assets/images/brand-3.png')" class="w-100" alt="brand logo" />
        </a>
        <a href="#" class="link w-20 pl-20 pl-md-30 pl-lg-50 pl-xl-65 pt-20 pt-md-30 pt-lg-55 pt-xl-60 pb-20 pb-md-30 pb-lg-50 pb-xl-54">
          <img :src="require('@/assets/images/brand-4.png')" class="w-100" alt="brand logo" />
        </a>
        </div>
      </nav>
    </div>
    <!-- </div> -->
  </header>
</template>
