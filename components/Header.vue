<template>
    <div>
    <div class="header bg-sky-800 p-5 flex justify-between lg:justify-around items-center uppercase">
        <img src="https://www.yesdok.com/img/headeryesdok.png" class="w-40" />
        <div class="hidden lg:flex justify-center space-x-16 flex-1">
            <NuxtLink to="/"><h1 class="text-white font-semibold text-xl cursor-pointer hover:text-blue-400">Beranda</h1></NuxtLink>
            <NuxtLink to="/diet"><h1 class="text-white font-semibold text-xl cursor-pointer hover:text-blue-400">diet</h1></NuxtLink>
            <NuxtLink to="/gayaHidup"><h1 class="text-white font-semibold text-xl cursor-pointer hover:text-blue-400">gaya hidup</h1></NuxtLink>
            <NuxtLink to="/pengasuhan"><h1 class="text-white font-semibold text-xl cursor-pointer hover:text-blue-400">pengasuhan</h1></NuxtLink>
        </div>
        <div class="hidden lg:flex">
            <h1 class="text-white font-semibold text-xl cursor-pointer hover:text-blue-400">Daftar / Masuk</h1>
        </div>
        <div class="lg:hidden">
            <font-awesome-icon :icon="['fas','bars']" class="text-white text-4xl" v-on:click="setNavbar"/>
        </div>
    </div>
    <div v-show="navbar === true" class="lg:hidden header p-10 uppercase">
        <NuxtLink to="/"><h1 class="text-white font-semibold text-2xl cursor-pointer hover:text-blue-400 mb-2">Beranda</h1></NuxtLink>
        <NuxtLink to="/diet"><h1 class="text-white font-semibold text-2xl cursor-pointer hover:text-blue-400 mb-2">diet</h1></NuxtLink>
        <NuxtLink to="/gayaHidup"><h1 class="text-white font-semibold text-2xl cursor-pointer hover:text-blue-400 mb-2">gaya hidup</h1></NuxtLink>
        <NuxtLink to="/pengasuhan"><h1 class="text-white font-semibold text-2xl cursor-pointer hover:text-blue-400 mb-2">pengasuhan</h1></NuxtLink>
    </div>
    </div>
</template>

<script>
export default {
    data(){
        return {
            navbar:false
        }
    },
    methods: {
        setNavbar: function(){
            this.navbar = !this.navbar
        }
    }
}
</script>

<style>

</style>