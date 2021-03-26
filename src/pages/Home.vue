<template>
  <div class="home">
    <Header />
    <Balenciaga/>
    <ThreeD/>
    <Booking/>
    <Evalution />
    <Footer />
  </div>
</template>

<script>
import Header from '@/components/Header'
import Balenciaga from '@/components/Balenciaga'
import ThreeD from '@/components/ThreeD'
import Booking from '@/components/Booking'
import Evalution from '@/components/Evalution'
import Footer from '@/components/Footer'

export default {
  name: 'Home',
  components: {
    Header: Header,
    Balenciaga: Balenciaga,
    ThreeD: ThreeD,
    Booking: Booking,
    Evalution: Evalution,
    Footer: Footer
  }
}
</script>
