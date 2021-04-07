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
      class="header__nav header__top w-100 w-md-20 px-30 py-50 h-100"
      :class="{ 'header__nav--show': showNav }"
    >
      <ul v-for="link in links" :key="link.id" @click="closeOrSleep">
        <a
          class="link text--right d-block text--10 text--sm-14 text--uppercase space--1 px-5 px-md-20 py-10 py-md-20"
          :href="link.url"
        >
          {{ link.name }}
        </a>
      </ul>
    </nav>
  </div>
</template>

<script>
import { mixin as clickaway } from 'vue-clickaway'
export default {
  mixins: [clickaway],
  data() {
    return {
      showNav: false,
      links: [
        {
          name: 'Link1',
          url: '#1'
        },
        {
          name: 'Link2',
          url: '#2'
        },
        {
          name: 'Link3',
          url: '#3'
        },
        {
          name: 'Link4',
          url: '#4'
        }
      ]
    }
  },
  methods: {
    closeOrSleep() {
      if ((this.showNav = true)) {
        this.showNav = false
      }
    },
    showMenu() {
      this.showNav = true
      window.addEventListener('scroll', this.closeMenu)
    },
    closeMenu() {
      this.showNav = false
      window.removeEventListener('scroll', this.closeMenu)
    }
  }
}
</script>
