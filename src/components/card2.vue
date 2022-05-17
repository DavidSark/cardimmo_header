<template>
  <!--DEUXIEME CARD TARPON BAY!-->
  <figure class="flex flex-col p-8">
    <img
      class="w-full h-auto object-cover rounded-t-lg"
      src="../assets\imagecard2.jpg"
      alt="img maison"
    />
    <figcaption
      class="
        relative
        flex flex-col
        p-5
        pt-7
        border-2 border-t-0
        rounded-b-lg
        border-indigo-100
        bg-white
      "
    >
      <div class="flex items-center">
        <div
          class="flex-grow-0 flex-shrink-0 text-2xl font-bold text-indigo-500"
        >
          $4800
        </div>
        <div class="h-8 text-base text-gray-500 pl-1 mt-2">/month</div>
      </div>

      <h3 class="text-2xl text-gray-900">Tarpon Bay</h3>
      <address class="not-italic font-normal text-gray-500">
        103 Lake Shores, Michigan, IN
      </address>

      <hr class="my-4 border-indigo-100" />
      <div class="flex flex-row justify-between text-sm">
        <div class="w-max">
          <bed class="h-5 w-5 mb-1 ml-1 inline-block" />4 Beds
        </div>
        <div class="w-max">
          <bath class="h-5 w-5 mb-1 ml-1 inline-block" />2 Baths
        </div>
        <div class="w-max">
          <zone class="h-5 w-5 mb-1 ml-1 inline-block" />6x7.5 m²
        </div>
      </div>
      <div
        class="
          absolute
          top-5
          right-3
          border-2 border-indigo-100
          place-items-center
          rounded-full
          H-7
          w-7
          grid
        "
      >
        <heart class="w-4" />
      </div>
    </figcaption>
  </figure>
</template>

<script>
import bath from "./icones/bath.vue";
import heart from "./icones/heart.vue";
import bed from "./icones/bed.vue";
import zone from "./icones/zone.vue";

export default {
  components: { bath, heart, bed, zone },
  bath,
};
</script>