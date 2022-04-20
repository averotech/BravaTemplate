<template>
<div>
  <Header/>
  <!-- <NewHeader /> -->
<HompePage />
<Footer/>
</div>
</template>

<script>
// header
import Header from './components/Header.vue'
import NewHeader from './components/NewHeader.vue'
// HomePage
import HompePage from './Pages/HomePages.vue'
// Footer
import Footer from './components/Footer.vue'
export default {
  name: 'App',
  components: {
    HompePage,Header,NewHeader,Footer
  }
}
</script>

