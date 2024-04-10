<script>
// qui va il js //
    import AppTitle from './components/AppTitle.vue';

    export default {
        components: {
            AppTitle
        }
    }
</script>


<template>
<!-- qui va l'html -->
    <main>
        <AppTitle></AppTitle>
    </main>
    
</template>


<style>
/* qui va il css */
    * {
        box-sizing: border-box;
        margin: 0;
        padding: 0;
    }
</style>