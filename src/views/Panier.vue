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
            <div class="mt-5 border-2 bg-white border-black h-[600px] w-[1000px]">
                <div class="text-center">
                    <h1>RÉCAPITULATIF</h1>
                    <div class="border-2 border-black mx-auto">
                        <h1>ETAT :</h1>

                        <button>Valider mon panier</button>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>