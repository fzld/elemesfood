<template>
    <div>
    <section class="fixed w-full px-8 text-gray-700 bg-white body-font z-10">
        <div class="container flex flex-row flex-wrap items-center justify-between py-5 mx-auto max-w-7xl">
            
            <a href="/" class="relative object-scale-down flex items-center w-1/2">
                <img src="~/static/logo.svg" alt="Elemes.id Logo">
            </a>

            <nav class="hidden lg:flex top-0 left-0 flex items-center justify-center w-full h-full py-5 -ml-0 space-x-5 text-base md:-ml-5 md:py-0 md:absolute">
                <nuxt-link to="/" class="relative font-medium leading-6 text-gray-600 transition duration-150 ease-out hover:text-gray-900" x-data="{ hover: false }" @mouseenter="hover = true" @mouseleave="hover = false">
                    Home
                </nuxt-link>
                <nuxt-link to="/about" class="relative text-sm font-medium leading-6 text-gray-600 transition duration-150 ease-out hover:text-gray-900" x-data="{ hover: false }" @mouseenter="hover = true" @mouseleave="hover = false">
                    About
                </nuxt-link>
                <nuxt-link to="/promotions" class="relative text-sm font-medium leading-6 text-gray-600 transition duration-150 ease-out hover:text-gray-900" x-data="{ hover: false }" @mouseenter="hover = true" @mouseleave="hover = false">
                    Promotions
                </nuxt-link>
                <nuxt-link to="blogs" class="relative text-sm font-medium leading-6 text-gray-600 transition duration-150 ease-out hover:text-gray-900" x-data="{ hover: false }" @mouseenter="hover = true" @mouseleave="hover = false">
                    Blogs
                </nuxt-link>
                <nuxt-link to="/contact" class="relative text-sm font-medium leading-6 text-gray-600 transition duration-150 ease-out hover:text-gray-900" x-data="{ hover: false }" @mouseenter="hover = true" @mouseleave="hover = false">
                    Contact Us
                </nuxt-link>
            </nav>
    
            <div class="relative z-10 inline-flex items-center space-x-2 md:ml-5 lg:justify-end">
                <nuxt-link to="/login" class="hidden md:inline-flex items-center justify-center px-4 py-2 text-sm font-medium text-gray-600 whitespace-no-wrap">
                    Masuk
                </nuxt-link>
                    <button class="btn inline-flex rounded-full shadow-sm">
                    <nuxt-link to="/register" class="px-4 py-2 text-xs font-med sm:text-sm text-white bg-elemes-green rounded-full shadow-sm hover:bg-elemes-green hover:bg-elemes-light-green">
                        Daftar Sekarang
                    </nuxt-link>
                    </button>
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