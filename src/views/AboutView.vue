<template>
  <div class="p-4">
    <div class="p-6 shadow-lg rounded-lg ">
      <div class="flex justify-center">
         <img class="w-24 h-24 ml-23 rounded-full object-cover " src="@/assets/girl.jpg" alt="ERROR">         
        </div>
    <p class="text-xl text-slate-900 text-center mt-6 px-3 font-medium">{{ $store.state.brand }} </p>
     <h3 class="text-sky-300 text-center font-semibold text-lg mt-4">{{ $store.state.text }}</h3>
     <h4 class="text-center text-fray-800 font-semibold text-lg">Staff Enginer,Algolia</h4>
      </div>
    </div>

 <div class="p-4">
   <input class="w-full border-4 p-2 mr-10" type="text" placeholder="enter your name" v-model="$store.state.text">
 </div>
  <div class="p-4">
   <input class="w-full border-4 p-2 mr-10" type="text" placeholder="enter your biografia" v-model="$store.state.brand">
 </div>
</template>