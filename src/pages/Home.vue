<template>
  <div class="home">
    <Header />
    <Strategy/>
    <Awesomer/>
    <Balenciaga/>
    <ThreeD/>
    <Booking/>
    <Evalution />
    <Footer />
  </div>
</template>

<script>
import Header from '@/components/Header'
import Strategy from '@/components/Strategy'
import Awesomer from '@/components/Awesomer'
import Balenciaga from '@/components/Balenciaga'
import ThreeD from '@/components/ThreeD'
import Booking from '@/components/Booking'
import Evalution from '@/components/Evalution'
import Footer from '@/components/Footer'

export default {
  name: 'Home',
  components: {
    Header: Header,
    Strategy: Strategy,
    Awesomer: Awesomer,
    Balenciaga: Balenciaga,
    ThreeD: ThreeD,
    Booking: Booking,
    Evalution: Evalution,
    Footer: Footer
  }
}
</script>
