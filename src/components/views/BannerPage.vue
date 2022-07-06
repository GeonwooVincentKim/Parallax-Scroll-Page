<template>
    <div>
        <full-page :backgroundColor="'red'">
            <div>
                hello world
            </div>
        </full-page>
    </div>
</template>

<script>
import FullPage from './components/FullPage.vue'

export default {
    name: 'BannerPage',
    components: { FullPage },
    

}
</script>
