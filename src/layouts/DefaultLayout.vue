<script>
import Header from '../components/Header.vue';
import Footer from '../components/Footer.vue';
export default {
    components: {
        Header, Footer
    }
}
</script>

<template>
    <div id="default-layout">
        <Header />
        <slot />
        <Footer />
    </div>
</template>

<!-- scoped div wont work here -->
<style scoped>
#default-layout {
    padding-top: 60px;
    padding-bottom: 60px;
}
</style>