<template>
   <section class="px-5 py-3 mt-5 mb-16">
      <div class="show flex justify-between items-end">
         <span class="text-blue-500 text-xs font-medium">
            Nearby Doctor <br />
            <small class="text-gray-400 text-xs font-medium" >Los Angeles, California</small>
         </span>
         <span class="text-gray-400 text-xs font-medium">
            See all
         </span>
      </div>
      
      <template v-for="card in 8" :key="card">
         <div class="show w-full bg-subsecondary mt-3 flex justify-between gap-2 items-end p-3 rounded-lg">
            <div>
               <img src="/profile.jpg" class="rounded-lg" width="80" />
            </div>
            <div class="text-blue-500 flex flex-wrap">
               <strong class="text-xs block w-full">Dr. Amanda Kirana</strong>
               <p class="text-xxs text-gray-400">Psychologist</p>
            </div>
            <small class="text-xxs text-gray-400 font-medium">
               0.5km
            </small>
         </div>
      </template>
   </section>
</template>