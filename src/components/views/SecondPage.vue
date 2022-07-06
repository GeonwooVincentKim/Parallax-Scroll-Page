<template>
    <div>
        <full-page :backgroundColor="'orange'">
            <div>
                hello world section2
            </div>
        </full-page>
    </div>
</template>

<script>
import FullPage from './components/FullPage.vue'

export default {
    name: 'SecondPage',
    components: { FullPage },
    

}
</script>
