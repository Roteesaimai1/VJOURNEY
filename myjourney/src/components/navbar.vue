<template>
    <div class="relative">
        <div :style="navbarStyle" class="fixed top-0 left-0 right-0 grid gap-4 grid-cols-3 rounded-r-2xl  border-b-2 border-pink-600 shadow-lg shadow-pink-500/20 brightness-125">
            <router-link to="/" class="antialiased  text-2xl m-3 font-semibold bg-clip-text text-transparent bg-gradient-to-r from-rose-500 hover:from-rose-500 hover:to-fuchsia-500 ">Home</router-link>
            <router-link to="/trip" class="antialiased text-2xl m-3 font-semibold bg-clip-text text-transparent bg-gradient-to-r from-rose-500 hover:from-rose-500 hover:to-fuchsia-500 ">Trip</router-link>
            <router-link to="/contact" class="antialiased text-2xl m-3 font-semibold bg-clip-text text-transparent bg-gradient-to-r from-rose-500 hover:from-rose-500 hover:to-fuchsia-500 ">Contact</router-link>
        </div>
    </div>
    
</template>

<script>
    export default {
        name:'navbar',     
        data() {
            return {
                navbarStyle: {
                    background: 'rgba(9, 9, 11, 0.8)', //bg navbar starter
                }
            }
        },
        mounted(){
            window.addEventListener('scroll', this.updateNavbarStyle)
        },
        beforeDestroy() {
            window.removeEventListener('scroll', this.updateNavbarStyle);
        },
        methods: {
            updateNavbarStyle() {
                const scrollPercent = (100 * window.scrollY) / (document.documentElement.scrollHeight - window.innerHeight);
                const navbarOpacity = 1 - (scrollPercent / 100);
                this.navbarStyle.background = `rgba((9, 9, 11, ${navbarOpacity})`;
            },    
        }   
    }
</script>


<style scoped>

</style>