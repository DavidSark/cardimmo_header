<template>
<div class=" hidden lg:visible lg:flex lg:justify-evenly">
    <div class="hidden lg:visible lg:grid lg:grid-cols-4 lg:w-10/12 lg:h-3/6 lg:bg-white lg:mt-6 lg:rounded-md">
        <div class="text-black">
            <div class="m-5  border-r-2 ">
            <p class="text-slate-500">Location</p>
            <p class="font-bold">New York, USA</p>
            </div>
        </div>

        <div class="text-black">
             <div class="m-5 border-r-2">
            <p class="text-slate-500">When</p>
            <p class="font-bold">Select Move-in Date</p>
            </div>
        </div>
        <div class="text-black">
            <div class="m-5 border-r-2">
            <p class="text-slate-500">Price</p>
            <p class="font-bold">$500-$2,500</p>
            </div>
        </div>
        <div class="text-black">
            <div class="m-5">
            <search></search>
            </div>
        </div>
    </div>
</div>
</template>

<script >

import search from "./icones/search.vue"

export default {
  name: "App",
  components: {
  search,
  },
};
</script>