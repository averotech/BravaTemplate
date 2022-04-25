<template>
<!-- homePage -->
<!-- <Slider /> -->
<!-- <OurProduct /> -->
<!-- <ChooseMacAndWatch /> -->
<!-- <BestOffer /> -->
<!-- <BestSeller/> -->
<!-- <LoginPage /> -->
<!-- <ProductListPage /> -->
<!-- <ProductDetaisPage /> -->
<MyProfile />
</template>
<script>

// homePage
import Slider from '../components/HomePage/Slider.vue';
import OurProduct from '../components/HomePage/OurProducts.vue'
import ChooseMacAndWatch from '../components/HomePage/ChooseMacAndWatch.vue'
import BestSeller from '../components/HomePage/BestSeller.vue'
import BestOffer from '../components/HomePage/BestOffer.vue'

// landingPage
import LoginPage from '../Pages/LandingPage/loginPage.vue'

// Product Page
import ProductListPage from './Products/ProductList.vue'
import ProductDetaisPage from './Products/ProductDetaisPage.vue'

// Profile
import MyProfile from './Profile/MyProfile.vue'

export default {
    setup() {
        
    },
    components:{Slider,OurProduct,ChooseMacAndWatch,BestSeller,BestOffer,LoginPage,ProductListPage,ProductDetaisPage,MyProfile}
}
</script>
