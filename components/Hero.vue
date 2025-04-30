<script setup>
import { ArrowRight } from 'lucide-vue-next';
</script>


<template>
    <div class="pt-34 flex items-start md:items-center justify-between  w-full gap-20 p-4 bg-gray-50 overflow-hidden h-[60vh]">
        <div class="flex-[0.5] ml-[-10vw] hidden md:block" >
            <img src="/amelia-hero-4.431832a.png"  class="h-full object-cover"/>
        </div>
        <div
            class="flex flex-1 items-start md:items-center justify-center flex-col w-full gap-4 p-4 bg-gray-50 max-w-[700px] text-center">

            <div class="text-gray-400 text-sm font-semibold">
                The #1 AI Headshot Generator for Professional Headshots
            </div>
            <div class="text-[#2A175D] font-bold text-4xl mt-3">
                Professional business headshots, without a physical photo shoot
            </div>
            <div class="text-lg">
                Get professional business headshots in minutes with our AI headshot generator. Upload photos, pick your
                styles & receive 100+ headshots.
            </div>
            <div class="flex gap-3 items-center">
                <div class="bg-[#FF6600] text-white font-bold text-md flex items-center gap-2 p-3 px-5 rounded-md">
                    Create your headshots now
                    <ArrowRight />
                </div>
                <span class="text-[#a5a4a7] font-semibold text-xs">OR</span>
                <div class="text-[#2A175D] font-semibold text-md border-[0.2px] rounded-md p-3 px-5 border-[#e7e7e7]">
                    Team Packages
                </div>
            </div>

            <div>
                <div class="">
                    <div class="flex gap-4 items-center">
                        <img src="/trustpilot.svg" alt="logo" class="w-30 inline" />
                        <div class="text-gray-700"> Rated <span class="font-semibold text-black">4.8</span> out of 5
                            with <span class="font-semibold text-black">2,302</span> reviews on</div>
                        <img src="/trust.png" alt="logo" class="w-24 inline" />
                    </div>
                    <div class="text-[0.9rem] text-gray-500 mt-3">
                        <span class="font-semibold">18M</span>
                        headshots created for
                        <span class="font-semibold">102,207+</span>
                        happy customers
                    </div>
                </div>
            </div>
            <div class="marquee-container">
                <div class="marquee flex gap-3 scale-[3]">
                    <img src="/logo-cloud-horizontal.e5e3772.png" alt="logo" class="marquee-img" />
                    <img src="/logo-cloud-horizontal.e5e3772.png" alt="logo" class="marquee-img" />
                </div>
            </div>
            <div class="mt-[-30px] md:hidden">
                <img src="/hero-male-female.3db6e78.png" />
            </div>

        </div>

        <div class="flex-[0.5] mr-[-10vw]  justify-end hidden md:flex">
            <img src="/hero-danny-6.dc40908.png" class="h-full object-cover" />
        </div>
    </div>
</template>
