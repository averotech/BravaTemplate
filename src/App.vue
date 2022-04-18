<template>
<div>
  <!-- <Header/> -->
  <!-- <NewHeader /> -->
<HompePage />
</div>
</template>

<script>
// header
import Header from './components/Header.vue'
import NewHeader from './components/NewHeader.vue'
// HomePage
import HompePage from './Pages/HomePages.vue'
export default {
  name: 'App',
  components: {
    HompePage,Header,NewHeader
  }
}
</script>

