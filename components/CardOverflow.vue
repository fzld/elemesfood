<template>
    <div>
       <!--smallcard section-->
    <h2 class="relative px-16 mx-auto max-w-7xl mt-12 text-2xl sm:text-4xl font-semibold leading-tight">Browse our category<br><span class="text-elemes-green">Recipe</span></h2>
    <section class="relative wrapper py-20 bg-white overflow-hidden">

        <!--card container-->
        <div class="relative px-16 mx-auto max-w-7xl">
            
            <div class="flex w-max-full h-max-full gap-6">

                <!--CARDs-->
                <div class="flex flex-col items-center justify-center col-span-1">
                    <div class="flex">
                        <div class="w-56 pt-6 rounded-md cursor-pointer shadow-lg bg-green-50 overflow-hidden hover:shadow-xl transform hover:scale-105 duration-500">
                          <img class="m-4 w-1/4 mx-auto" src="~/assets/images/icon/cupcake.png" alt="" />
                          <div class="p-4 bg-green-50 text-center">
                            <h1 class="font-bold text-sm">Cupcake</h1>
                            <p class="mb-6 font-light text-xs">22 items</p>
                          </div>
                        </div>
                      </div>
                </div>

                <!--CARDs-->
                <div class="flex flex-col items-center justify-center col-span-1">
                  <div class="flex">
                      <div class="w-56 pt-6 rounded-md cursor-pointer shadow-lg bg-blue-50 overflow-hidden hover:shadow-xl transform hover:scale-105 duration-500">
                        <img class="m-4 w-1/4 mx-auto" src="~/assets/images/icon/pizza.png" alt="" />
                        <div class="p-4 bg-blue-50 text-center">
                          <h1 class="font-bold text-sm">Pizza</h1>
                          <p class="mb-6 font-light text-xs">25 items</p>
                        </div>
                      </div>
                    </div>
                </div>

                <!--CARDs-->
                <div class="flex flex-col items-center justify-center col-span-1">
                  <div class="flex">
                      <div class="w-56 pt-6 rounded-md cursor-pointer shadow-lg bg-indigo-100 overflow-hidden hover:shadow-xl transform hover:scale-105 duration-500">
                        <img class="m-4 w-1/4 mx-auto" src="~/assets/images/icon/kebab.png" alt="" />
                        <div class="p-4 bg-indigo-100 text-center">
                          <h1 class="font-bold text-sm">Kebab</h1>
                          <p class="mb-6 font-light text-xs">12 items</p>
                        </div>
                      </div>
                    </div>
                </div>

                <!--CARDs-->
                <div class="flex flex-col items-center justify-center col-span-1">
                  <div class="flex">
                      <div class="w-56 pt-6 rounded-md cursor-pointer shadow-lg bg-red-100 overflow-hidden hover:shadow-xl transform hover:scale-105 duration-500">
                        <img class="m-4 w-1/4 mx-auto" src="~/assets/images/icon/salmon.png" alt="" />
                        <div class="p-4 bg-red-100 text-center">
                          <h1 class="font-bold text-sm">Salmon</h1>
                          <p class="mb-6 font-light text-xs">22 items</p>
                        </div>
                      </div>
                    </div>
                </div>

                <!--CARDs-->
                <div class="flex flex-col items-center justify-center col-span-1">
                  <div class="flex">
                      <div class="w-56 pt-6 rounded-md cursor-pointer shadow-lg bg-yellow-200 overflow-hidden hover:shadow-xl transform hover:scale-105 duration-500">
                        <img class="m-4 w-1/4 mx-auto" src="~/assets/images/icon/doughnut.png" alt="" />
                        <div class="p-4 bg-yellow-200 text-center">
                          <h1 class="font-bold text-sm">Doughnut</h1>
                          <p class="mb-6 font-light text-xs">11 items</p>
                        </div>
                      </div>
                    </div>
                </div>

                <!--CARDs-->
                <div class="flex flex-col items-center justify-center col-span-1">
                  <div class="flex">
                      <div class="w-56 pt-6 rounded-md cursor-pointer shadow-lg bg-green-100 overflow-hidden hover:shadow-xl transform hover:scale-105 duration-500">
                        <img class="m-4 w-1/4 mx-auto" src="~/assets/images/icon/doughnut.png" alt="" />
                        <div class="p-4 bg-green-100 text-center">
                          <h1 class="font-bold text-sm">Doughnut</h1>
                          <p class="mb-6 font-light text-xs">11 items</p>
                        </div>
                      </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!--scrollover buttons-->
    <div class="hidden md:block text-right px-48 mt-2">
      <button class="px-6 py-3 mb-3 text-sm text-white bg-elemes-green rounded-full hover:bg-elemes-light-green">
        <i class="fas fa-arrow-left"></i> Prev
      </button>
      <button class="px-6 py-3 mb-3 text-sm text-white bg-elemes-green rounded-full hover:bg-elemes-light-green">
        Next <i class="fas fa-arrow-right"></i>
      </button>
    </div> 
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>

</style>