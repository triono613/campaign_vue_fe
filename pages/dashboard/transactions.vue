<template>
  <div class="project-page">
   <section class="dashboard-header pt-5">
     <div class="container mx-auto relative">
       <header class="flex items-center">
         <div style="height: 54px" class="pr-5">
           <img src="/logo.svg" alt="logo" class="h-full" />
         </div>
         <ul class="flex items-center">
           <li>
           
         <nuxt-link
               class="text-white hover:text-teal-500 text-lg px-4 py-3"
               to="/"
               >Home</nuxt-link>
           </li>
           <li>
             <nuxt-link
               class="text-white hover:text-teal-500 text-lg px-4 py-3"
               to="/pricing"
               >Project</nuxt-link
             >
           </li>
           <li>
             <nuxt-link
               class="text-white hover:text-teal-500 text-lg px-4 py-3"
               to="/features"
               >Features</nuxt-link
             >
           </li>
           <li>
             <nuxt-link
               class="text-white hover:text-teal-500 text-lg px-4 py-3"
               to="/story"
               >Success Stories</nuxt-link
             >
           </li>
         </ul>
         <ul class="flex ml-auto items-center mt-2">
           <li>
             <nuxt-link
               to="/register"
               class="inline-block bg-transparent border-white border hover:bg-white hover:bg-opacity-25 text-white font-light w-40 text-center px-6 py-1 text-lg rounded-full mr-4"
             >
               Sign Up
             </nuxt-link>
           </li>
           <li>
             <nuxt-link
               to="/login"
               class="inline-block bg-transparent border-white border hover:bg-white hover:bg-opacity-25 text-white font-light w-40 text-center px-6 py-1 text-lg rounded-full"
             >
               My Account
             </nuxt-link>
           </li>
         </ul>
       </header>
     </div>
   </section>
   <section class="container mx-auto pt-8">
        <div class="flex justify-between items-center mb-6">
          <div class="w-3/4 mr-6">
            <h2 class="text-4xl text-gray-900 mb-2 font-medium">Dashboard</h2>
            <ul class="flex mt-2">
              <li class="mr-6">
                <a
                  class="text-gray-500 hover:text-gray-800"
                  href="/dashboard/index.html"
                >
                  Your Projects
                </a>
              </li>
              <li class="mr-6">
                <a
                  class="text-gray-800 font-bold"
                  href="/dashboard/transactions.html"
                >
                  Your Transactions
                </a>
              </li>
            </ul>
          </div>
        </div>
        <hr />
        <div class="block mb-2">
          <div class="w-full lg:max-w-full lg:flex mb-4">
            <div
              class="h-48 lg:h-auto lg:w-48 flex-none bg-cover rounded-t lg:rounded-t-none lg:rounded-l text-center overflow-hidden"
              style="background-color: #bbb"
            ></div>
            <div
              class="w-full border-r border-b border-l border-gray-400 lg:border-l-0 lg:border-t lg:border-gray-400 bg-white rounded-b lg:rounded-b-none lg:rounded-r p-8 flex flex-col justify-between leading-normal"
            >
              <div>
                <div class="text-gray-900 font-bold text-xl mb-1">
                  Cari Uang Buat Gunpla
                </div>
                <p class="text-sm text-gray-600 flex items-center mb-2">
                  Rp. 200.000.000 &middot; 12 September 2020
                </p>
              </div>
            </div>
          </div>
        </div>
      </section>
   <div class="cta-clip -mt-20"></div>
   <section class="call-to-action bg-purple-progress pt-64 pb-10"></section>
   <Footer />
 </div>
</template>