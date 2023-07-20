<template>
    <div class="grid gap-4 grid-cols-3 bg-zinc-950 rounded-r-2xl  border-b-2 border-pink-600 shadow-lg shadow-pink-500/20 brightness-125">
        <router-link to="/" class="antialiased  text-3xl m-3 font-semibold bg-clip-text text-transparent bg-gradient-to-r from-rose-500 hover:from-rose-500 hover:to-fuchsia-500 ">Home</router-link>
        <router-link to="/trip" class="antialiased text-3xl m-3 font-semibold bg-clip-text text-transparent bg-gradient-to-r from-rose-500 hover:from-rose-500 hover:to-fuchsia-500 ">Trip</router-link>
        <router-link to="/about" class="antialiased text-3xl m-3 font-semibold bg-clip-text text-transparent bg-gradient-to-r from-rose-500 hover:from-rose-500 hover:to-fuchsia-500 ">About</router-link>
    </div>
</template>

<script>
    export default {
        name:'navbar',        
    }
</script>

<style scoped>

</style>