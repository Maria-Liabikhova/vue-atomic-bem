<template>
  <div v-on-clickaway="closeOrSleep">
    <button
      type="button"
      class="header__button"
      :class="{ 'header__button--none': showNav }"
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
        class="link d-block text--10 text--sm-14 text--uppercase space--1 px-5 py-10 px-md-20 py-md-20"
        >link1</a
      >
      <a
        href="#"
        class="link d-block text--10 text--sm-14 text--uppercase space--1 px-5 py-10 px-md-20 py-md-20"
        >link2</a
      >
      <a
        href="#"
        class="link d-block text--10 text--sm-14 text--uppercase space--1 px-5 py-10 px-md-20 py-md-20"
        >link3</a
      >
      <a
        href="#"
        class="link d-block text--10 text--sm-14 text--uppercase space--1 px-5 py-10 px-md-20 py-md-20"
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
      window.addEventListener('scroll', this.closeMenu) //так мы учитываем наличие скролла и запускаем механизм закрытия модального окна
    },
    closeMenu() {
      this.showNav = false
      console.log('scroll')
      window.removeEventListener('scroll', this.closeMenu) //так мы перестаем отслеживать наличие скролла, чтобы не запускать лишних механизов и не перегружать приложение
    }
  }
}
</script>
