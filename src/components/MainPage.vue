<template>
    <div class="wrapper">
        <banner-page />
        <second-page />
    </div>
</template>

<script>
import BannerPage from './views/BannerPage.vue'
import SecondPage from './views/SecondPage.vue'

export default {
    name: 'MainPage',
    components: { BannerPage, SecondPage },
    mounted() {
    }
}
</script>

<style scoped>

</style>
