<template>
        <h1>{{ title }}</h1>    
</template>

<script>
    export default {
        name: 'AppTitle',  
        data() {
            return {
                title: 'La mia prima app con Vite!'
            }
        },
        methods: {
        
        }, 
        mounted() {
            
        }, 
        components: {
            
        }
    }
</script>

<style scoped>
    h1{
        color: white;
        font-size: 4em;
        text-align: center;
    }
</style>