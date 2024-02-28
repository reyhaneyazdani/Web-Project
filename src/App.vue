<script setup>
import HomePage from './components/HomePage.vue'
const menu = [{
  index:1,
  title : "درباره ی ما"
},
{
  index:2,
  title : "صلاحیت ها"
},
{
  index:1,
  title : "پروژه ها"
},
{
  index:1,
  title : " ارتباط با ما "
},
]
</script>

<template>
 
<div
      class="h-1/2 lg:h-screen bg-gradient-to-t from-indigo-900 relative overflow-hidden"
    > 
      <nav class="w-full fixed top-0 z-10 ">
        <div class="container mx-auto py-5 flex items-center justify-between">
          <div class="flex items-center gap-1">
            <img class="w-32" src="/logo png.png" alt="" />
          </div>
        </div>
      </nav>
      <div class="fixed right-16 bottom-2 z-10 border-dashed border-2 border-[#9747FF] px-3 py-2 rounded-lg">
        <div v-for="(item, index) in menu" :key="index" class="py-1 px-8 text-center bg-[#D9D9D9]/50 text-white rounded-full my-4">
          <h1 class="tracking-wide text-lg">{{item.title }}</h1>
        </div>
        <p class="text-xs text-white pb-1 font-light">مهندسین مشاور فربوم شهر پارس</p>
  
      </div>
     
      <img
        class="object-cover w-full absolute "
        src="/Page 24-2.png"
        alt=""
      />
   
    <!-- <img
      class="object-cover  py-20 w-full h-screen  relative"
      src="/iranian-building-85236987-10.jpg"
      alt=""
    /> -->
  </div>
    <div class="mb-16">
  <HomePage  />
</div>  
</template>

<style scoped>

</style>
