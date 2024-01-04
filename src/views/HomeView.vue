<script setup>
import Navbar from '@/components/Navbar.vue';
import Footer from '@/components/Footer.vue';
</script>

<template>
  <main class="bg-black py-20">
    <Navbar />
    <div class="w-full mt-[180px] mb-60 px-28 flex flex-col items-center justify-center">
      <div class="absolute left-32 top-56">
        <img src="/icons/ux-designer.svg" alt="">
      </div>
      <div class="absolute right-52 top-[680px] transform rotate-[30deg] w-[182px]">
        <img src="/icons/ux-designer-2.svg" alt="">
      </div>
      <div class="absolute left-24 top-[460px]">
        <img src="/icons/arrow.svg" alt="">
      </div>
      <div class="absolute left-52 top-[750px] w-[113px] h-[75px] transform -rotate-[30deg]" style="filter: blur(3px);">
        <img src="/icons/ux-designer.svg" alt="">
      </div>
      <div class="absolute right-[38%] top-[930px] w-[113px] h-[75px]">
        <img src="/icons/arrow-2.svg" alt="">
      </div>
      <div class="ini-h1 flex flex-col w-fit mb-14">
        <h1 class="cabinet-font tracking-[-0.035em] text-white text-[116px] text-center"><span class="text-deg">O</span>ne Step Closer To <span class="block text-center text-transparent bg-clip-text bg-gradient-to-b from-white to-slate-900">Your Dreams Job</span></h1>
      </div>
      <p class="text-center text-white text-lg mb-12">Let Us Help You Find A Job That Suits You The Best!</p>
      <div class="flex gap-8 items-center mb-24">
        <div class="flex w-44 h-14 items-center justify-center rounded-md bg-gradient-to-b from-purple-400 via-purple-500 to-indigo-500">
          <button class="w-full h-full border-none text-white text-base font-medium">
            <router-link to="/">Get Started</router-link>
          </button>
        </div>
        <div class="flex w-36 h-12">
          <router-link class="w-full flex items-center" to="/">
            <button class="w-full flex flex-row items-center justify-between">
              <img src="/icons/video-square.svg" alt="">
              <p class="text-white text-lg">Our Story</p>
            </button>
          </router-link>
        </div>
      </div>
      <div class="flex gap-12">
        <div class="flex flex-col justify-center">
          <h3 class="cabinet-font text-white text-4xl">20M+</h3>
          <p class="text-white text-center text-lg">Users</p>
        </div>
        <div class="flex flex-col justify-center">
          <h3 class="cabinet-font text-white text-4xl">500K+</h3>
          <p class="text-white text-center text-lg">Jobs</p>
        </div>
        <div class="flex flex-col justify-center">
          <h3 class="cabinet-font text-white text-4xl">100+</h3>
          <p class="text-white text-center text-lg">Partners</p>
        </div>
      </div>
    </div>
    <div class="w-full h-[196px] flex items-center justify-center mb-36">
      <div class="w-full h-[140px] absolute -rotate-2 bg-gradient-to-br from-purple-400 via-purple-500 to-indigo-500"></div>
      <div class="w-full h-[140px] flex items-center justify-center rotate-2 bg-gradient-to-b from-purple-400 via-purple-500 to-indigo-500">
        <img src="/icons/sponsorship.svg" class="-rotate-2" alt="">
      </div>
    </div>
    <div class="mb-20 flex px-28 justify-center gap-28">
      <div class="">
        <img src="/images/music.png" alt="">
      </div>
      <div class="flex flex-col justify-center w-[32%]">
        <h3 class="cabinet-font ini-h3 mb-5 text-[40px] text-white">Work With <span class="text-purple-500">Exciting</span> Companies</h3>
        <p class="text-white text-lg  mb-5">Et Sapien Enim Congue Interdum Pulvinar Non Sed. Ac Aungue Netus Tellus Semper.</p>
        <div class="flex w-[200px] h-[60px] items-center justify-center rounded-md bg-gradient-to-b from-purple-400 via-purple-500 to-indigo-500">
          <button class="w-full h-full border-none text-white text-base font-medium">
            <router-link to="/">Get Started</router-link>
          </button>
        </div>
      </div>
    </div>
    <Footer />
  </main>
</template>

<style scoped>
@import url('https://fonts.cdnfonts.com/css/cabinet-grotesk');

.ini-h1 {
  line-height: 0.9;
}

.ini-h3 {
  line-height: 1;
}

.cabinet-font {
  font-family: 'Cabinet Grotesk', sans-serif;
  font-weight: 900;
}

.text-deg {
  background: linear-gradient(150deg, transparent 50%, rgb(255, 255, 255) 50%);
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
  font-family: 'Cabinet Grotesk', sans-serif;
  font-weight: 900;
}</style>
