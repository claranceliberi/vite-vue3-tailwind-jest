<script setup lang="ts">
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
</script>

<template>
    <div class="bg-slate-100 w-full min-h-[100vh]">
        <!-- component -->
        <nav class="flex justify-end">
            <div class="">
                <a class="px-10 py-1 cursor-pointer" href="https://github.com/claranceliberi/vite-vue3-tailwind-jest">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="24" height="24">
                        <path fill="none" d="M0 0h24v24H0z" />
                        <path
                            d="M12 2C6.475 2 2 6.475 2 12a9.994 9.994 0 0 0 6.838 9.488c.5.087.687-.213.687-.476 0-.237-.013-1.024-.013-1.862-2.512.463-3.162-.612-3.362-1.175-.113-.288-.6-1.175-1.025-1.413-.35-.187-.85-.65-.013-.662.788-.013 1.35.725 1.538 1.025.9 1.512 2.338 1.087 2.912.825.088-.65.35-1.087.638-1.337-2.225-.25-4.55-1.113-4.55-4.938 0-1.088.387-1.987 1.025-2.688-.1-.25-.45-1.275.1-2.65 0 0 .837-.262 2.75 1.026a9.28 9.28 0 0 1 2.5-.338c.85 0 1.7.112 2.5.337 1.912-1.3 2.75-1.024 2.75-1.024.55 1.375.2 2.4.1 2.65.637.7 1.025 1.587 1.025 2.687 0 3.838-2.337 4.688-4.562 4.938.362.312.675.912.675 1.85 0 1.337-.013 2.412-.013 2.75 0 .262.188.574.688.474A10.016 10.016 0 0 0 22 12c0-5.525-4.475-10-10-10z"
                        /></svg
                ></a>
            </div>
        </nav>
        <div class="flex items-center justify-center h-full min-h-[80vh]">
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
    </div>
</template>
