<template>
  <header class="header h-100">
    <div class="container h-100">
      <div class="d-flex flex-column justify-content-between h-100">
        <div class="d-flex justify-content-between pt-30 pb-30  mb-xl-120 mb-lg-80 mb-sm-50 mb-xs-30">
          <a href="#" class="link d-flex align-items-start w-70 w-sm-40">
            <img
              :src="require('@/assets/images/logo.png')"
              alt=""
              class="w-15"
            />
            <span class="text--whites w-90 text--md-30 text--md-36 lh-30 lh--md-36">webovio</span>
          </a>
          <nav class="nav header__top d-block d-sm-flex flex-wrap">
            <a
              href="#"
              class="link d-block text--14 text--uppercase space--1 px-8"
              >link1</a
            >
            <a
              href="#"
              class="link d-block text--14 text--uppercase space--1 px-8"
              >link2</a
            >
            <a
              href="#"
              class="link d-block text--14 text--uppercase space--1 px-8"
              >link3</a
            >
            <a
              href="#"
              class="link d-block text--14 text--uppercase space--1 px-8"
              >link4</a
            >
          </nav>
        </div>
        <main class="d-block w-90 w-md-50">
          <p class="text--whites text--10 text--md-14 lh-14">A place where</p>
          <h1 class="text--36 text--sm-50 text--xl-60 text--whites mb-20">
            A creative agency for redemptive brands
          </h1>
          <h2 class="text--whites text--10 text--sm-14 text--md-16 mb-45">
            Anteelo is a leading strategic design firm that builds powerful
            digital solutions for startups and enterprises.
          </h2>
          <a href="#" class="link text--12 text--sm-16 link--yellow link--arrow mb-40 mb-sm-90">Get in touch</a>
        </main>
        <nav
          class="d-flex align-items-center justify-content-between px-25 px-md-35 px-lg-50 header__brands"
        >
          <a href="#" class="link w-20">
            <img :src="require('@/assets/images/brand-1.png')" class="w-100" alt="brand logo" />
          </a>
          <a href="#" class="link w-20">
            <img :src="require('@/assets/images/brand-2.png')" class="w-100" alt="brand logo" />
          </a>
          <a href="#" class="link w-20">
            <img :src="require('@/assets/images/brand-3.png')" class="w-100" alt="brand logo" />
          </a>
          <a href="#" class="link w-20">
            <img :src="require('@/assets/images/brand-4.png')" class="w-100" alt="brand logo" />
          </a>
          <a href="#" class="link w-20">
            <img :src="require('@/assets/images/brand-5.png')" class="w-100" alt="brand logo" />
          </a>
        </nav>
      </div>
    </div>
  </header>
</template>
