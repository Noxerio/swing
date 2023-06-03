<template>
    <div class="bg-slate-900">
        <div class="container mx-auto p-10 flex flex-col items-center">
            <h2 class="text-center text-6xl text-amber-300 font-title">Nápoje</h2>
            <p class="text-white text-xl opacity-70 text-center p-5">Lorem ipsum dolor sit amet, consectetuer adipiscing elit.</p>
            <img src="/hr.png" class="w-48">
        </div>
        
        <div class="md:grid justify-center items-strech gap-12 md:grid-cols-2 lg:grid-cols-3 container mx-auto p-10">
            <DrinksService :title="'Mletá káva'" :img="'coffe.png'"/>
            <DrinksService :title="'Míchané drinky'" :img="'drinks.png'" :style="'border-2 border-amber-400 scale-105'" :sticker="true"/>
            <DrinksService :title="'Čepované pivo'" :img="'beer.png'" :logos="true"/>
        </div>
    </div>
</template>