<script setup>
const props = defineProps(['title' , 'img', 'style', 'sticker', 'logos'])
</script>
<template>
    <div :class="'text-center bg-slate-800 rounded-xl my-5 p-7 flex flex-col gap-4 drop-shadow-xl hover:scale-105 transition ease-in-out delay-5 duration-1000 ' + props.style">
        <div v-if="props.sticker == true" class="absolute text-amber-400 uppercase px-4 py-2 rounded-xl border-2 border-amber-400 font-title animate-bounce	">
            Happy hours
        </div>
        <img :src="'/drinks/' + props.img" class="p-16" >
        <h3 class="text-white text-3xl font-bold font-title">{{props.title}}</h3>
        
        <div v-if="props.logos == true" class="grid grid-cols-2 gap-8 opacity-70">
            <img class="p-5" src="/drinks/logos/pilsner.png">
            <img class="p-5" src="/drinks/logos/radegast.png">
        </div>
        <p v-else class="text-white text-xl opacity-70">Lorem ipsum dolor sit amet, consectetuer adipiscing elit. </p>
    </div>
</template>