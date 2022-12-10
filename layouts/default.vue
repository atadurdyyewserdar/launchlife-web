<template>
  <div class="main">
    <Header/>
    <nuxt/>
    <Footer/>
  </div>
</template>

<script>

import Header from '@/components/header.vue'
import Footer from '@/components/footer.vue'

export default{
  name: 'DefaultLayout',
  components:{
    Header,
    Footer,
  }
}
</script>