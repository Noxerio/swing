<template>
    <div class="container mx-auto p-10 grid grid-cols-2 gap-10 mt-20">
        <div class="flex flex-col gap-8 items-center justify-center">
            <h2 class="text-amber-400 font-title text-6xl text-center">Rezervujte si stůl</h2>
            <div class="grid grid-cols-2 gap-8">
                <div class="flex flex-col items-center gap-8 bg-slate-800 rounded-xl p-10">
                    <Icon name="bx:bxs-phone" color="white" size="46"/>
                     <p class="text-white font-bold text-2xl"> +420 774 229 884</p>
                </div>
                <div class="flex flex-col items-center gap-8 bg-slate-800 rounded-xl p-10">
                    <Icon name="ic:baseline-mail" color="white" size="46"/>
                     <p class="text-white font-bold text-2xl">info@swingbarostrava.cz</p>
                </div>
            </div>
            <img src="/hr.png" class="w-48">
            <h3 class="text-white font-title text-4xl">Kde nás najdete?</h3>
            <p class="text-white opacity-75 text-xl">Škroupova 1108/10, 702 00 Moravská Ostrava a Přívoz</p>
            
        </div>
        <div class="text-white border-2 border-white p-10 rounded-xl">
            <h2 class="text-center font-title text-4xl text-amber-400">Otevírací doba</h2>
            <table class="w-full m-5 text-2xl table-auto border-separate border-spacing-4">
                <tr class="border-b-2 border-dashed">
                    <td class="w-1/2">Pondělí</td><td>Zavřeno</td>
                </tr>
                <tr>
                    <td class="w-1/2">Úterý</td><td>18:00 - 23:00</td>
                </tr>
                <tr>
                    <td class="w-1/2">Středa</td><td>18:00 - 23:00</td>
                </tr>
                <tr>
                    <td class="w-1/2">Čtvrtek</td><td>18:00 - 23:00</td>
                </tr>
                <tr>
                    <td class="w-1/2">Pátek</td><td>18:00 - 23:00</td>
                </tr>
                <tr>
                    <td class="w-1/2">Sobota</td><td>18:00 - 23:00</td>
                </tr>
                <tr>
                    <td class="w-1/2">Neděle</td><td>Zavřeno</td>
                </tr>
            </table>
        </div>
    </div>
</template>