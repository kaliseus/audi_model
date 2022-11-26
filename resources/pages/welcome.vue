<template>
    <Navbar></Navbar>
    <Swiper></Swiper>
    <featured-vehicles></featured-vehicles>
    <Filter-home></Filter-home>
    <Widgets></Widgets>

</template>

<script>
import Navbar from "../js/components/Navbar.vue";
import Swiper from "../js/components/Swiper.vue";
import FilterHome from "../js/components/Filterhome.vue";
import FeaturedVehicles from "../js/components/Featured-vehicles.vue";
import Widgets from "../js/components/Widgets.vue";

export default {
    name: "app",
    components: {Widgets, FeaturedVehicles, FilterHome, Swiper, Navbar},
}
</script>

<style scoped>

</style>
