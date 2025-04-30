<script setup>
import { Menu } from 'lucide-vue-next';
</script>

<template>
    <div class="flex items-center justify-center w-full  fixed  border-b border-[0.2px] border-[#eeeeee]">
        <nav
            class="p-3 px-4 md:px-8 max-w-[900px] lg:max-w-[1200px] flex items-center gap-10 justify-between backdrop-blur-lg  w-full">

            <div class="flex gap-8 items-center">
                <div class="flex gap-2 items-center">
                    <img src="/loho.svg" alt="logo" class="w-40" /> <a href="#"
                        class="bg-[#64CDCF] font-bold text-white flex items-center text-[0.6rem] h-4 rounded-xl px-2 uppercase">Hiring</a>
                </div>
                <div class="md:flex gap-5 text-lg text-[#1C145D] font-semibold hidden ">
                    <div>
                        For teams
                    </div>
                    <div>
                        Examples
                    </div>
                    <div>Pricing</div>
                </div>
            </div>
            <div class="flex gap-5">
                <button class="bg-[#1C145D] text-white font-medium text-sm p-4 py-1 rounded-md">
                    Create
                </button>
                <button class="border-[0.2px] border-[#e7e7e7] p-3 py-1 rounded-md">
                    <Menu />
                </button>

            </div>
        </nav>
    </div>
</template>