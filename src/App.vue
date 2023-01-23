<script setup lang="ts">
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
</script>

<template>
    <div class="bg-slate-100 flex items-center justify-center w-full h-[100vh]">
        <!-- component -->
        <div class="w-1/2">
            <div class="w-full shadow-2xl subpixel-antialiased rounded h-64 bg-black border-black mx-auto">
                <div class="flex items-center h-6 rounded-t bg-gray-100 border-b border-gray-500 text-center text-black" id="headerTerminal">
                    <div class="flex ml-2 items-center text-center border-red-900 bg-red-500 shadow-inner rounded-full w-3 h-3" id="closebtn"></div>
                    <div class="ml-2 border-yellow-900 bg-yellow-500 shadow-inner rounded-full w-3 h-3" id="minbtn"></div>
                    <div class="ml-2 border-green-900 bg-green-500 shadow-inner rounded-full w-3 h-3" id="maxbtn"></div>
                    <div class="mx-auto pr-16" id="terminaltitle">
                        <p class="text-center text-sm">Terminal</p>
                    </div>
                </div>
                <div class="pl-1 pt-1 h-auto text-green-200 font-mono text-xs bg-black" id="console">
                    <p class="pb-1">Last Modification: Tue Jan 24 00:06:29 CAT 2023 on ttys002</p>
                    <p class="pb-1">claranceliberi:vue3-vite-ts-template$</p>
                </div>
            </div>
        </div>
    </div>
</template>
