<script setup lang="ts">
</script>

<template>
    <div class="min-h-[100vh] h-full bg-gradient-to-t from-[#C4B454] to-[#FFFFFF]">
        <RouterLink to="/carte">
            <h1 class="text-center mt-2 font-bold text-white text-lg rounded-lg ml-4 border-2 border-black bg-[#C4B454] max-w-28 p2 text-white hover:bg-black active:bg-white active:text-black">RETOUR</h1>
        </RouterLink>
        <div>
            <h1 class="text-center font-bold text-[#C4B454] text-6xl">PANIER</h1>
        </div>
        <div class="flex justify-center">
            <div class="mt-5 border-2 flex bg-white border-black h-[600px] w-[1000px]">
                <div class="border-r-2 border-black w-[600px] overflow-scroll overflow-x-hidden">
                    <p>PANIER</p>
                    <div class="border">
                        <h1 class="font-bold text-lg">TOTAL :</h1>
                    </div>
                </div>
                <div class="flex mx-auto items-center">
                    <div class="text-center">
                            <h1 class="text-lg font-bold">RÉCAPITULATIF</h1>
                        <div class="border-2 border-black max-w-[400px]">
                            <h1 class="text-left pl-2 text-lg font-bold">ETAT :</h1>

                            <button class="border border-black rounded mt-3 p-4 bg-[#C4B454] text-white text-lg">Valider mon panier</button>
                            <img class="mx-auto" src="../assets/BarappPaiement.PNG" />
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>