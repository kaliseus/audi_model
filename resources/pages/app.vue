<template>
    <Navbar></Navbar>
    <Swiper></Swiper>

</template>

<script>
import Navbar from "../js/components/Navbar.vue";
import Swiper from "../js/components/Swiper.vue";

export default {
    name: "app",
    components: {Swiper, Navbar},
}
</script>

<style scoped>

</style>
