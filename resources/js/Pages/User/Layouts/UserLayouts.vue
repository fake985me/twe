<script setup>
import { onMounted } from 'vue'
import { initFlowbite } from 'flowbite'
import Header from './Header.vue';
import Footer from './Footer.vue';
import Hero from './Hero.vue';
import NavBar from './navBar.vue';

// initialize components based on data attribute selectors
onMounted(() => {
    initFlowbite();
})



</script>
<template>
    <!-- header -->
    <NavBar></NavBar>
    <!-- end -->
    <!-- main content -->

    <slot />
    <!-- end -->
    <!-- footer -->

    <Footer></Footer>

    <!-- end -->
</template>
