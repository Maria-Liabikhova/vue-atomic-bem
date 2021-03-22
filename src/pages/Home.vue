<template>
  <div class="home">
    <page-header />
    <evalution />
    <Footer />
  </div>
</template>

<script>
import Header from '@/components/Header'
import Evalution from '@/components/Evalution'
import Footer from '@/components/Footer'

export default {
  name: 'Home',
  components: {
    'page-header': Header,
    evalution: Evalution,
    Footer: Footer
  }
}
</script>
