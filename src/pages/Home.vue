<template>
  <div class="home">
    <page-header />
    <evalution />
  </div>
</template>

<script>
import Header from '@/components/Header'
import Evalution from '@/components/Evalution'

export default {
  name: 'Home',
  components: {
    'page-header': Header,
    evalution: Evalution
  }
}
</script>
