<template>
  <Navbar></Navbar>
  <Main></Main>
  <Footer></Footer>
</template>

<script>
import Main from './components/Main.vue';
import Navbar from './components/Navbar.vue';
import Footer from './components/Footer.vue'
export default {
    components: { Navbar, Main, Footer }
}
</script>

<style>
</style>
