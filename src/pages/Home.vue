<template>
  <div class="home">
    <Header />
    <Booking/>
    <Evalution />
    <Footer />
  </div>
</template>

<script>
import Header from '@/components/Header'
import Booking from '@/components/Booking'
import Evalution from '@/components/Evalution'
import Footer from '@/components/Footer'

export default {
  name: 'Home',
  components: {
    Header: Header,
    Evalution: Evalution,
    Footer: Footer,
    Booking: Booking
  }
}
</script>
