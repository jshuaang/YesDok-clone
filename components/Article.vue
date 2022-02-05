<template>
    <div>
    <div class="hidden lg:flex py-10 px-20 w-11/12 m-auto">
        <!-- left -->
        <div>
        <img :src="image" class="w-60 h-52 mr-5 rounded-xl">
        </div>
        <!-- right -->
        <div class="space-y-5 w-3/4">
         <NuxtLink :to="'article/'+id"><h1 id="title-article" class="text-4xl font-semibold uppercase">{{title}}</h1></NuxtLink>
        <p class="text-2xl ">{{desc}}</p>
        <div class="flex space-x-5">
            <div class="tag-yellow w-40 p-1 rounded-full bg-blue-100 text-center">
            <p class="uppercase text-white font-semibold">{{category}}</p>
            </div>
            <div id="date-article" class="w-40 p-1 rounded-full text-center">
            <p class="font-semibold"><font-awesome-icon :icon="['fas','clock']" class="mr-2"/>{{date}}</p>
            </div>
        </div>
        </div>
    </div>
    <div class="lg:hidden py-10 px-10 w-11/12 m-auto">
        <div class="relative">
        <img :src="image" class="w-full h-60 mr-5 rounded-xl">
        <!-- text -->
        <div class="absolute top-20 left-5 w-11/12">
        <div class="flex space-x-5 mb-5">
            <div class="w-32 p-1 rounded-xl bg-blue-100 text-center tag-yellow">
            <p class="uppercase text-white font-semibold">{{category}}</p>
            </div>
            <div class="text-gray-800 w-40 p-1 rounded-lg bg-gray-100 text-center">
            <p class="font-semibold"><font-awesome-icon :icon="['fas','clock']" class="mr-2"/>{{date}}</p>
            </div>
        </div>
        <NuxtLink :to="'article/'+id"><h1 id="title-article" class="text-lg bg-white font-semibold uppercase p-1">{{title}}</h1></NuxtLink>
        </div>
        </div>
    </div>
    </div>
</template>

<script>
export default {
    props: ['image', 'title', 'desc', 'category', 'date', 'id']
}
</script>

<style>

</style>