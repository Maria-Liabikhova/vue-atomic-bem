<template>
  <div v-on-clickaway="closeOrSleep">
    <button
      type="button"
      class="collapse__button mr-10 px-2 px-md-5 py-2 py-md-5"
      :class="{ 'collapse__button--none': showNav }"
      @click="showMenu"
    >
      <img
        :src="require('@/assets/images/hicon.svg')"
        alt="links menu button"
      />
    </button>
    <nav
      class="header__nav header__top w-25 w-sm-20 px-30 py-50 h-100"
      :class="{ 'header__nav--show': showNav }"
    >
      <a
        href="#"
        class="link d-block text--10 text--sm-14 text--uppercase space--1 px-5 px-md-20 py-10 py-md-20"
        >link1</a
      >
      <a
        href="#"
        class="link d-block text--10 text--sm-14 text--uppercase space--1 px-5 px-md-20 py-10 py-md-20"
        >link2</a
      >
      <a
        href="#"
        class="link d-block text--10 text--sm-14 text--uppercase space--1 px-5 px-md-20 py-10 py-md-20"
        >link3</a
      >
      <a
        href="#"
        class="link d-block text--10 text--sm-14 text--uppercase space--1 px-5 px-md-20 py-10 py-md-20"
        >link4</a
      >
    </nav>
  </div>
</template>

<script>
import { mixin as clickaway } from 'vue-clickaway'
export default {
  mixins: [clickaway],
  data() {
    return {
      showNav: false
    }
  },
  methods: {
    closeOrSleep() {
      if (this.showNav === true) {
        this.showNav = false
        console.log('click')
      }
    },
    showMenu() {
      this.showNav = true
      window.addEventListener('scroll', this.closeMenu)
    },
    closeMenu() {
      this.showNav = false
      console.log('scroll')
      window.removeEventListener('scroll', this.closeMenu)
    }
  }
}
</script>
