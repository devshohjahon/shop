<template>
    <div class="bg-indigo-400 p-4 flex justify-center lg:justify-start gap-2">
   <router-link v-for="yollonma in yollonmalar" :key="yollonma" class="bg-green-400 text-white py-1 px-4
   rounded-full font-bold border border-white hover:bg-white hover:text-indigo-500 hover:border-indigo-600 duration-300"
   :to="yollonma.manzil">{{ yollonma.nom }}</router-link>
    </div>
</template>
<script>
export default {
    name:"NavBar",
    data(){
    return{
        yollonmalar:[
            {
                manzil:'/',
                nom:'Bosh sahifa'
            },
            {
                manzil:'/about',
                nom:'Haqida'
            },
        

        ]
    }
    }
}
</script>