<template>
  <div class="home">
    <Header />
    <ThreeD/>
    <Booking/>
    <Evalution />
    <Footer />
  </div>
</template>

<script>
import Header from '@/components/Header'
import ThreeD from '@/components/ThreeD'
import Booking from '@/components/Booking'
import Evalution from '@/components/Evalution'
import Footer from '@/components/Footer'

export default {
  name: 'Home',
  components: {
    Header: Header,
    ThreeD: ThreeD,
    Booking: Booking,
    Evalution: Evalution,
    Footer: Footer
  }
}
</script>
