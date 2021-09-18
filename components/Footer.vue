<template>
    <div>
        <section class="hidden lg:block px-16">
      <footer class="bg-green-50 rounded-3xl">

        <div class="container px-12 py-24 ml-12 flex md:items-center lg:items-start md:flex-row md:flex-nowrap flex-wrap flex-col">
           
          <!--elemesprofile-->
          <div class="w-1/4 flex-shrink-0 md:mx-0 mx-auto text-left">
            <a href="#_" class="relative object-scale-down z-10 flex items-center w-full"><img src="~/static/logo.svg" alt=""></a>
            <p class="mt-4 text-xs text-gray-600">Jl. Prof. DR. Satrio No.7, RT.3/RW.3, Karet Kuningan,<br>
              Kecamatan Setiabudi, Kota Jakarta Selatan, <br>
              Daerah Khusus Ibukota Jakarta 12950</p>
            <ul class="flex mt-6 text-xl text-elemes-green gap-6">
              <li><i class="fas fa-envelope"></i></li>
              <li><i class="fas fa-phone"></i></li>
              <li><i class="fab fa-instagram"></i></li>
            </ul>
          </div>

          <div class="flex-grow flex flex-wrap md:pl-20 -mb-10 md:mt-0 mt-10 md:text-left text-center">
            
            <!--categories-->
            <div class="lg:w-1/4 md:w-1/2 w-full">
              <h2 class="font-bold text-md mb-3">Categories</h2>
              <nav class="list-none mb-10">
                <li>
                  <a class="text-xs hover:text-elemes-green" href="#">Cupcake</a>
                </li>
                <li>
                  <a class="text-xs hover:text-elemes-green" href="#">Pizza</a>
                </li>
                <li>
                  <a class="text-xs hover:text-elemes-green" href="#">Kebab</a>
                </li>
                <li>
                  <a class="text-xs hover:text-elemes-green" href="#">Salmon</a>
                </li>
                <li>
                  <a class="text-xs hover:text-elemes-green" href="#">Doughnut</a>
                </li>
              </nav>
            </div>

            <!--ABOUT US-->
            <div class="lg:w-1/4 md:w-1/2 w-full">
              <h2 class="font-bold text-md mb-3">About Us</h2>
              <nav class="list-none mb-10">
                <li>
                  <a class="text-xs hover:text-elemes-green" href="#">About Us</a>
                </li>
                <li>
                  <a class="text-xs hover:text-elemes-green" href="#">FAQ</a>
                </li>
                <li>
                  <a class="text-xs hover:text-elemes-green" href="#">Report Problem</a>
                </li>
              </nav>
            </div>

            <!--Newsletter-->
            <div class="lg:w-1/3">
              <h2 class="font-bold text-md mb-3">Newsletter</h2>
              <nav class="list-none mb-10">
                <li>
                  <p class="text-xs">Get now free 50% discount for alll products on your first order</p>
                </li>
                <li>
                  <form class="bg-white rounded-lg text-sm my-4">
                    <input placeholder="Your email address" class="w-3/4 rounded-md px-2">
                    <button class="bg-elemes-green text-white px-0 xl:px-2 py-2 rounded-r-lg" type="submit">
                        SEND
                    </button>
                </form>
                </li>
                <li>
                  <p><i class="far fa-envelope text-elemes-green text-base"><span class="text-black font-Rubik text-xs">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;elemesid@gmail.com</span></i></p>
                </li>
                <li>
                  <p><i class="fas fa-phone text-elemes-green text-base"><span class="text-black font-Rubik text-xs font-light">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0888 1111 2222 </span></i></p>
                </li>
              </nav>
            </div>

          </div>
        </div>
      </footer>

      <div class="bg-white">
        <div class="container mx-auto py-4 px-5">
          <p class="text-xs text-center">© 2021 ELEMES.ID —
            <span class="text-gray-400 ml-1">ALL RIGHTS RESERVED</span>
          </p>
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