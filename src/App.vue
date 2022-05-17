<template>
  <!--HEADER AVEC L'ICONE MENU RESPONSIVE!-->

  <div class="bg-indigo-50">
    <div class="flex flex-grow-0 flex-shrink-0 items-center bg-white">
      <header1 />
      <div class="hidden lg:visible lg:flex flex-grow space-x-7 items-center flex-shrink-0 lg:mr-11">
        <ul class="hidden lg:visible lg:flex flex-grow space-x-7 justify-evenly">
            <li>Rent</li>
            <li>Buy</li>
            <li>Sell</li>
            <li>Manage Property</li>
            <li>Ressources</li>
        </ul>
                <div class="flex ">
                   </div>
                  <div class=" hidden lg:visible lg:flex lg:items-center lg:justify-evenly lg:rounded-xl lg:border-2 lg:border-indigo-500 lg:bg-white lg:w-36
                   lg:text-center lg:font-inter lg:font-semibold lg:text-indigo-500 lg:h-14
                    
            "> Login
            </div>
                  <div class=" hidden lg:visible lg:flex lg:items-center lg:justify-evenly lg:rounded-xl lg:bg-indigo-500 lg:w-36 lg:h-14 lg:text-center lg:font-inter lg:font-semibold lg:text-white lg:m-4 
                    
            "> Sign up 
           
        </div>

      </div>
      <div class="mt-4 ml-10 absolute top-0 right-0 mr-4">
        <menuicon class="lg:hidden" />
      </div>
    </div>
    <hr class="my-7 border-gray-300 -mt-0" />

    <div class="flex flex-col lg:flex-row justify-between lg:items-center">
      <!--TAG LINE!-->

      <p class="text-center font-inter text-2xl font-bold pt-11 pb-6 lg:ml-10">
        Search properties to rent
      </p>

      <!--SEARCH BAR ET SEARCH LOCATION RESPONSIVE!-->

      <div class="pl-8 pt-4 pr-8 lg:flex-auto lg:max-w-sm">
        <searchBar />
      </div>
    </div>

    <div class="pl-8 pt-6 pr-8 lg:hidden">
      <searchlocation />
    </div>

    <menunav></menunav>
    

    <div
      class="
        grid grid-flow-row-dense grid-cols-[repeat(auto-fit,minmax(500px,1fr))]
      "
    >
      <card />
      <card2 />
    </div>

    <!--ICONES ET FLECHES PERMETTANT DE CHANGER DE PAGES + RESPONSIVE!-->
    <div class="flex pr-3 flex-wrap justify-center pb-10">
      <arrow1 />
      <div class="pr-5"></div>
      <div class="rounded-2xl bg-indigo-900 w-6">
        <p class="text-white text-center font-semibold">1</p>
      </div>
      <div class="pr-5"></div>

      <div class="rounded-2xl bg-white w-6">
        <p class="text-gray-500 text-center font-semibold">2</p>
      </div>
      <div class="pr-5"></div>
      <threedot />
      <div class="pr-5"></div>
      <div class="rounded-2xl bg-white w-6">
        <p class="text-gray-500 text-center font-semibold">10</p>
      </div>
      <div class="pr-5"></div>
      <arrow2 />
    </div>
  </div>

  <!--FOOTER MOBILE FIRST NON RESPONSIVE!-->
  <footer1 />
</template>
<script >
import bouton from "./components/bouton.vue";
import card from "./components/card.vue";
import card2 from "./components/card2.vue";
import footer1 from "./components/footer.vue";
import searchBar from "./components/searchbar.vue";
import header1 from "./components/header1.vue";
import menu from "./components/menu.vue";
import searchlocation from "./components/searchlocation.vue";
import pagebar from "./components/pagebar.vue";
import arrow1 from "./components/icones/arrowleft.vue";
import arrow2 from "./components/icones/arrowright.vue";
import threedot from "./components/icones/threedot.vue";
import menuicon from "./components/icones/menuicon.vue";
import searchicon from "./components/icones/searchicon.vue";
import menunav from "./components/menunav.vue"
import search from "./components/icones/search.vue"

export default {
  name: "App",
  components: {
    bouton,
    card,
    card2,
    footer1,
    searchBar,
    header1,
    menu,
    searchlocation,
    pagebar,
    arrow1,
    arrow2,
    threedot,
    menuicon,
    menunav,
    search,
  },
};
</script>