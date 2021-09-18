<template>
    <div>
    <section class="herobg px-16 lg:px-40 mx-auto pt-32 bg-white">
        
        <!--container hero-->
        <div class="container items-center mx-auto">
          <div class="flex flex-wrap-reverse items-center sm:-mx-3">

             <!--left--> 
            <div class="w-full md:w-1/2 md:px-3">
              <div class="w-full pb-6 space-y-6 sm:max-w-md lg:max-w-lg md:space-y-4 lg:space-y-8 xl:space-y-9 sm:pr-5 lg:pr-0 md:pb-0">
                <h1 class="relative text-5xl font-bold tracking-tight text-elemes-green xl:text-6xl">
                  Good food us
                  <span class="relative block text-elemes-green xl:inline">Good mood</span>
                </h1>
                <p class="mx-auto text-base text-gray-500 sm:max-w-md lg:text-xl md:max-w-3xl">I would think that conserving our natural resources should be a conservative position: Not to waste food, and not to throw away a lot of the food that we buy.</p>
                <div class="relative flex flex-row space-x-4">
                  <button class="flex items-center w-auto px-6 py-3 mb-3 text-xs font-semibold sm:text-sm text-white bg-elemes-green rounded-full hover:bg-elemes-light-green">
                    Daftar Sekarang
                  </button>
                  <button class="flex items-center w-auto px-6 py-3 mb-3 text-xs font-semibold sm:text-sm text-gray-500 bg-gray-100 rounded-full hover:bg-gray-200 hover:text-gray-600">
                    About Us
                  </button>
                </div>
              </div>
            </div>

            <!--right-->
            <div class="relative w-full md:w-1/2">
              <div class="w-full h-auto overflow-hidden">
                  <img src="~/static/hero.png">
                </div>
            </div>
            
          </div>
        </div>
      </section>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>

</style>