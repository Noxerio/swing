<template>
    <div class="grid grid-cols-2 gap-8 mx-auto container p-10">
        <div class="grid grid-cols-2 gap-8">
            <EventsService/>
            <EventsService/>
            <EventsService/>
            <EventsService/>
        </div>
        <div class="container mx-auto p-10 flex flex-col items-center justify-center">
            <h2 class="text-center text-6xl text-amber-300 font-title">Nadcházející údálosti</h2>
            <p class="text-white text-xl opacity-70 text-center p-5">Lorem ipsum dolor sit amet, consectetuer adipiscing elit.</p>
            <img src="/hr.png" class="w-48">
            <div class="flex justify-center gap-8">
                <button class="text-slate-800 bg-amber-300 font-title px-5 py-3 rounded-xl mt-20 text-xl">Zakoupit lístky</button>
                <button class="border-2 border-white text-white font-title px-5 py-3 rounded-xl mt-20 text-xl">Seznam událostí</button>
            </div>
        </div>
        
    </div>
</template>