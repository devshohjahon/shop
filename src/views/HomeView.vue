<template>
<div class="p-4 text-3xl font-bold text-green-700 ">
  {{
   $store.state.brand
  }}
</div>
 <div class="p-4">
   <input class="w-full border-4 p-2 mr-10" type="text" placeholder="write anything" v-model="$store.state.brand">
 </div>
</template>


