<script>
import AppHeader from "./section/AppHeader.vue";
import AppMain from "./section/AppMain.vue";
import AppFooter from "./section/AppFooter.vue";


export default {
    components: {
        AppHeader,
        AppMain,
        AppFooter
    },
    data() {
        return {
            
        };
    },
    methods: {

    },
    mounted() {

    },
};
</script>

<template>
    <div class="bg-primary">
        <h1 class="text-white">Project Laravel-9 Vue-3 Vite</h1>
    </div>
    <AppHeader />
    <AppMain />
    <AppFooter />

</template>

<style lang="scss" scoped>
    
</style>
