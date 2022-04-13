<template>
<div>
  <Header/>
<!-- <HompePage /> -->
</div>
</template>

<script>
// header
import Header from './components/Header.vue'

// HomePage
import HompePage from './Pages/HomePages.vue'
export default {
  name: 'App',
  components: {
    HompePage,Header
  }
}
</script>

