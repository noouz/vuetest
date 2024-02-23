<script setup>
// import TheWelcome from '../components/TheWelcome.vue'
</script>

<template>
  <main>
    <div class="container bg-slate-500">
        <div class="nav">
            <div class="nav-logo">
                <img src="./img/icon.JPG" alt="">
            </div>
            <input type="checkbox" id="nav-menu">
            <label for="nav-menu" class="nav-menu">
                <div class="nav-line line1"></div>
                <div class="nav-line line2"></div>
                <div class="nav-line line3"></div>
            </label>
            <ul class="nav-list-show">
                <li class="nav-list-btn-show"><a href="https://www.google.com.tw/?hl=zh_TW" target="_blank">Google</a></li>
                <li class="nav-list-btn-show"><a href="https://www.youtube.com/" target="_blank">Youtube</a></li>
                <li class="nav-list-btn-show"><a href="https://www.pexels.com/zh-tw/" target="_blank">Pexels</a></li>
            </ul>
            <ul class="nav-list">
                <li class="nav-list-btn"><a href="https://www.google.com.tw/?hl=zh_TW" target="_blank">Google</a></li>
                <li class="nav-list-btn"><a href="https://www.youtube.com/" target="_blank">Youtube</a></li>
                <li class="nav-list-btn"><a href="https://www.pexels.com/zh-tw/" target="_blank">Pexels</a></li>
            </ul>
        </div>
        
        <div class="main">
            <div class="main-content">
                <div class="main-img main-content-item1"></div>
                <div class="main-img main-content-item2"></div>
                <div class="main-img main-content-item3"></div>
            </div>
        </div>
    </div>
  </main>
</template>
