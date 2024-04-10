<template>
    <header>
        <section class="jumbotron">
            <div class="container">
                <AppTitle />
            </div>
        </section>
    </header>
</template>

<script>
    import AppTitle from './AppTitle.vue'
    export default {
        name: 'AppHero',
        data() {
            return {
                
            }
        }, 
        methods: {
            
        }, 
        mounted() {
            
        }, 
        components: {
            AppTitle
        }
    }
</script>

<style scoped>
    .jumbotron{
        background-color: rgb(108, 108, 154);
    }
</style>