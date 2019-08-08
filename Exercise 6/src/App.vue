<template>
    <div class="container">
        <Header />
        <hr>
        <HomePageMain />
        <hr>
        <Footer />
    </div>
</template>

<script>
    import Header from './components/Header.vue';
    import Footer from './components/Footer.vue';
    import HomePageMain from './components/HomePageMain.vue';

    export default {

        components: {
            Header,
            Footer,
            HomePageMain
        }
    }
</script>

<style>

</style>
