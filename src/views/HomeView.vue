<script setup>
// import TheWelcome from '../components/TheWelcome.vue'
</script>

<template>
  <main>
    <div class="w-full h-screen bg-slate-300 flex flex-col box-border md:flex md:flex-row">
        <div class="nav bg-slate-600 shrink-0 flex p-5 h-1/6 justify-between items-center  md:flex-col md:items-center md:pt-20 md:w-1/4 md:h-full md:justify-start ">
            <div class="nav-logo rounded-full md:mb-5">
                <img src="https://placehold.jp/100x100.png" alt="" class="rounded-full w-[80px] md:w-[100px]">
            </div>
            <!-- <ul class="nav-list-show hidden">
                <li class="nav-list-btn-show"><a href="https://www.google.com.tw/?hl=zh_TW" target="_blank">Google</a></li>
                <li class="nav-list-btn-show"><a href="https://www.youtube.com/" target="_blank">Youtube</a></li>
                <li class="nav-list-btn-show"><a href="https://www.pexels.com/zh-tw/" target="_blank">Pexels</a></li>
            </ul> -->
            <ul class="nav-list leading-8 flex gap-x-3 md:flex-col md:gap-y-3">
                <li class="bg-red-400 p-3 flex rounded justify-center text-white"><a href="https://www.google.com.tw/?hl=zh_TW" target="_blank">Google</a></li>
                <li class="bg-red-400 p-3 flex rounded justify-center text-white"><a href="https://www.youtube.com/" target="_blank">Youtube</a></li>
                <li class="bg-red-400 p-3 flex rounded justify-center text-white"><a href="https://www.pexels.com/zh-tw/" target="_blank">Pexels</a></li>
            </ul>
        </div>
        
        <div class=" bg-slate-50 h-lvh w-full flex justify-center items-center md:w-lvw md:h-screen">
            <div class=" bg-slate-500 w-11/12 h-5/6 md:w-5/6 md:h-5/6 flex flex-wrap ">
                <div class="bg-red-400 w-full h-3/6 xl:w-4/12 xl:h-full "></div>
                <div class="bg-red-500 w-6/12 h-3/6 xl:w-4/12 xl:h-full"></div>
                <div class="bg-red-600 w-6/12 h-3/6 xl:w-4/12 xl:h-full "></div>
            </div>
        </div>
    </div>
  </main>
</template>

<style scoped>
    .nav{
        @apply 
    }
</style>
