<template>
    <div class="container">
        <nav>
            <h1> <nuxt-link to="/"> User Auth.</nuxt-link></h1>
            <nuxt-link to="/"><img src="../../assets/logo.svg" alt="" srcset=""></nuxt-link>
        </nav>
    </div>
</template>

<script>
export default {
    data() {
        return {
            
        }
    },
    methods: {
        
    },
}
</script>

<style scoped>
nav{
    display: flex;
    justify-content: space-between;
    align-items: flex-end;
    width: 90%;
    margin: auto;
    height: 10vh;
}
h1, a{
    color: #00C58E;
    font-weight: 400;
    font-size: clamp(20px, 2vw, 30px);
    text-decoration: none;
}
</style>
