<template>
    <div>
    <div class="block lg:hidden fixed bottom-0 w-full px-7 bg-white shadow-lg rounded-2xl">
      <div class="flex">
          <div class="flex-1 group">
              <nuxt-link to="/" class="flex items-end justify-center text-center mx-auto px-4 pt-2 w-full text-gray-400 group-hover:text-elemes-green border-b-2 border-transparent group-hover:elemes-green">
                  <span class="block px-1 pt-1 pb-2">
                      <i class="fas fa-home text-2xl pt-1 mb-1 block"></i>
                      <span class="block text-xs pb-1">Home</span>
                  </span>
              </nuxt-link>
          </div>
          <div class="flex-1 group">
              <nuxt-link to="/promotions" class="flex items-end justify-center text-center mx-auto px-4 pt-2 w-full text-gray-400 group-hover:text-elemes-green border-b-2 border-transparent group-hover:elemes-green">
                  <span class="block px-1 pt-1 pb-2">
                      <i class="fas fa-tags text-2xl pt-1 mb-1 block"></i>
                      <span class="block text-xs pb-1">Promotions</span>
                  </span>
              </nuxt-link>
          </div>
          <div class="flex-1 group">
              <nuxt-link to="/about" class="flex items-end justify-center text-center mx-auto px-4 pt-2 w-full text-gray-400 group-hover:text-elemes-green border-b-2 border-transparent group-hover:elemes-green">
                  <span class="block px-1 pt-1 pb-2">
                      <i class="far fa-compass text-2xl pt-1 mb-1 block"></i>
                      <span class="block text-xs pb-1">Others</span>
                  </span>
              </nuxt-link>
          </div>
      </div>
    </div>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>

</style>