<template>
    <div class="container mx-auto p-10 mb-24 ">
        <h2 class="text-amber-300 font-title text-center mb-10 text-6xl">Míchačky všeho druhu</h2>
        <img src="/hr.png" class="w-48 mx-auto mb-20">
        <swiper
         :modules="[SwiperAutoplay, SwiperEffectCreative]"
            :slides-per-view="5"
            :space-between="50"
            :loop="true"
            :autoplay="{
                delay: 1000,
                
                }"
        >
            <swiper-slide class="bg-slate-700 rounded-xl p-10 text-center">
                <img src="/drinks/drinks.png">
                <h3 class="pt-5 font-title text-2xl text-white">Margarita</h3>
                <p class="opacity-75 text-amber-400 font-bold">127,- | HH 63,-</p>
            </swiper-slide>
            <swiper-slide class="bg-slate-700 rounded-xl p-10 text-center">
                <img src="/drinks/drinks.png">
                <h3 class="pt-5 font-title text-2xl text-white">Margarita</h3>
                <p class="opacity-75 text-amber-400 font-bold">127,- | HH 63,-</p>
            </swiper-slide>
            <swiper-slide class="bg-slate-700 rounded-xl p-10 text-center">
                <img src="/drinks/drinks.png">
                <h3 class="pt-5 font-title text-2xl text-white">Margarita</h3>
                <p class="opacity-75 text-amber-400 font-bold">127,- | HH 63,-</p>
            </swiper-slide>
            <swiper-slide class="bg-slate-700 rounded-xl p-10 text-center">
                <img src="/drinks/drinks.png">
                <h3 class="pt-5 font-title text-2xl text-white">Margarita</h3>
                <p class="opacity-75 text-amber-400 font-bold">127,- | HH 63,-</p>
            </swiper-slide>
            <swiper-slide class="bg-slate-700 rounded-xl p-10 text-center">
                <img src="/drinks/drinks.png">
                <h3 class="pt-5 font-title text-2xl text-white">Margarita</h3>
                <p class="opacity-75 text-amber-400 font-bold">127,- | HH 63,-</p>
            </swiper-slide>
            <swiper-slide class="bg-slate-700 rounded-xl p-10 text-center">
                <img src="/drinks/drinks.png">
                <h3 class="pt-5 font-title text-2xl text-white">Margarita</h3>
                <p class="opacity-75 text-amber-400 font-bold">127,- | HH 63,-</p>
            </swiper-slide>
            <swiper-slide class="bg-slate-700 rounded-xl p-10 text-center">
                <img src="/drinks/drinks.png">
                <h3 class="pt-5 font-title text-2xl text-white">Margarita</h3>
                <p class="opacity-75 text-amber-400 font-bold">127,- | HH 63,-</p>
            </swiper-slide>
    </swiper>
    <div class="flex justify-center">
        <button class="text-slate-800 bg-amber-300 font-title px-5 py-3 rounded-xl mt-20 text-xl">Nápojový lístek</button>
    </div>
    
    </div>
   
  </template>