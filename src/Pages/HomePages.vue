<template>
<!-- homePage -->
<Slider />
<!-- <OurProduct /> -->
<!-- <ChooseMacAndWatch /> -->
<BestOffer />
<BestSeller/>
</template>
<script>

// homePage
import Slider from '../components/HomePage/Slider.vue';
import OurProduct from '../components/HomePage/OurProducts.vue'
import ChooseMacAndWatch from '../components/HomePage/ChooseMacAndWatch.vue'
import BestSeller from '../components/HomePage/BestSeller.vue'
import BestOffer from '../components/HomePage/BestOffer.vue'
export default {
    setup() {
        
    },
    components:{Slider,OurProduct,ChooseMacAndWatch,BestSeller,BestOffer}
}
</script>
