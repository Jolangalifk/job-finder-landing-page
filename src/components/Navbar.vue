<template>
    <div class="flex justify-between items-center  px-28" style="font-family: 'Plus Jakarta Sans', sans-serif;">
        <div class="flex gap-12">
            <div class="flex w-28 h-9">
                <img src="/icons/logo.svg" alt="" class="w-full">
            </div>
            <div class="flex">
                <ul class="flex flex-row items-center gap-8">
                    <li class="flex text-white text-base font-medium text-transparent bg-clip-text bg-gradient-to-b from-white via-white to-white hover:from-red-300 hover:via-purple-500 hover:to-indigo-500 transition duration-500 ease-in-out">
                        <router-link to="/">Home</router-link>
                    </li>
                    <li class="flex text-white text-base font-medium text-transparent bg-clip-text bg-gradient-to-b from-white via-white to-white hover:from-red-300 hover:via-purple-500 hover:to-indigo-500 transition duration-500 ease-in-out">
                        <router-link to="/">About Us</router-link>
                    </li>
                    <li class="flex text-white text-base font-medium text-transparent bg-clip-text bg-gradient-to-b from-white via-white to-white hover:from-red-300 hover:via-purple-500 hover:to-indigo-500 transition duration-500 ease-in-out">
                        <router-link to="/">Pricing</router-link>
                    </li>
                    <li class="flex text-white text-base font-medium text-transparent bg-clip-text bg-gradient-to-b from-white via-white to-white hover:from-red-300 hover:via-purple-500 hover:to-indigo-500 transition duration-500 ease-in-out">
                        <router-link to="/">Features</router-link>
                    </li>
                </ul>
            </div>
        </div>
        <div class="flex gap-4">
            <div class="flex w-44 h-14 items-center justify-center rounded-md bg-gradient-to-b from-purple-400 via-purple-500 to-indigo-500">
                <button class="w-full h-full border-none text-white text-base font-medium">
                    <router-link to="/">Register</router-link>
                </button>
            </div>
            <div class="flex w-44 h-14 items-center justify-center p-[2px] rounded-md bg-gradient-to-b from-purple-400 via-purple-500 to-indigo-500">
                <button class="w-full h-full border-none text-white text-base font-semibold rounded-md bg-black">
                    <router-link to="/register">Get A Quote</router-link>
                </button>
            </div>
        </div>
    </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:ital,wght@0,200;0,300;0,400;0,500;0,600;0,700;0,800;1,200;1,300;1,400;1,500;1,600;1,700;1,800&display=swap');
</style>