<template>
  <header class="header  h-100">
    <div class="container h-100">
      <div class="d-flex flex-column justify-content-between h-100">
        <div
          class="d-flex align-items-center justify-content-lg-between pt-30 pb-30"
        >
          <a href="#" class="link link--logo d-flex align-items-center  mb-120">
            <img
              :src="require('@/assets/images/logo.png')"
              alt=""
              class="img"
            />
            <span class="text--whites text--36 lh--36">webovio</span>
          </a>
          <nav class="nav header__top d-flex flex-wrap">
            <a
              href="#"
              class="link text--14 text--lg-16 text--uppercase space--1 px-8"
              >link1</a
            >
            <a
              href="#"
              class="link text--14 text--lg-16 text--uppercase space--1 px-8"
              >link2</a
            >
            <a
              href="#"
              class="link text--14 text--lg-16 text--uppercase space--1 px-8"
              >link3</a
            >
            <a
              href="#"
              class="link text--14 text--lg-16 text--uppercase space--1 px-8"
              >link4</a
            >
          </nav>
        </div>
        <main class="d-block w-50">
          <p class="text--whites text--14 lh-14">A place where</p>
          <h1 class="text--60 text--whites mb-20">
            A creative agency for redemptive brands
          </h1>
          <h2 class="text--whites text--16 mb-45">
            Anteelo is a leading strategic design firm that builds powerful
            digital solutions for startups and enterprises.
          </h2>
          <a href="#" class="link link--yellow link--arrow mb-90">Get in touch</a>
        </main>
        <nav
          class="d-flex align-items-center justify-content-between px-50 header__brands"
        >
          <a href="#" class="link link--img">
            <img :src="require('@/assets/images/brand-1.png')" alt="brand logo" />
          </a>
          <a href="#" class="link link--img">
            <img :src="require('@/assets/images/brand-2.png')" alt="brand logo" />
          </a>
          <a href="#" class="link link--img">
            <img :src="require('@/assets/images/brand-3.png')" alt="brand logo" />
          </a>
          <a href="#" class="link link--img">
            <img :src="require('@/assets/images/brand-4.png')" alt="brand logo" />
          </a>
          <a href="#" class="link link--img">
            <img :src="require('@/assets/images/brand-5.png')" alt="brand logo" />
          </a>
        </nav>
      </div>
    </div>
  </header>
</template>
