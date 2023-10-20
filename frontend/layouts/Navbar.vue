<script>
export default {
  name: 'Navbar'
}
</script>

<template>
  <nav class="bg-white border-gray-200 pt-8 pb-5 dark:bg-gray-900 border-b">
      <div class="flex flex-wrap items-center justify-between max-w-screen-xl px-7 mx-auto">
          <a href="#" class="flex items-center">
              <img src="~/assets/images/logo/primary-logo.png" class="h-6 mr-3 sm:h-9" alt="Landwind Logo">
          </a>
          <div class="flex items-center lg:order-2">
              <div class="hidden mt-2 mr-4 sm:inline-block">
                  <span></span>
              </div>

              <div>
                <a href="https://discord.gg/zuYkajb6ez" target="_blank" class="bg-white hover:bg:dark-500">
                  <i class="ri-discord-fill inine-block text-2xl mx-4"></i>
                </a>
                <a href="https://github.com/Ngoding-Bareng-Org" target="_blank" class="bg-white hover:bg:dark-500">
                  <i class="ri-github-fill inine-block text-2xl"></i>
                </a>
              </div>
              <button data-collapse-toggle="mobile-menu-2" type="button"
          class="inline-flex items-center p-2 ml-1 text-sm text-gray-500 rounded-lg lg:hidden hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-gray-200 dark:text-gray-400 dark:hover:bg-gray-700 dark:focus:ring-gray-600"
          aria-controls="mobile-menu-2" aria-expanded="true">
          <span class="sr-only">Open main menu</span>
          <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
            <path fill-rule="evenodd"
              d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z"
              clip-rule="evenodd"></path>
          </svg>
          <svg class="hidden w-6 h-6" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
            <path fill-rule="evenodd"
              d="M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z"
              clip-rule="evenodd"></path>
          </svg>
        </button>
          </div>
          <div class="items-center justify-between w-full lg:flex lg:w-auto lg:order-1" id="mobile-menu-2">
              <ul class="flex flex-col mt-4 font-medium lg:flex-row lg:space-x-8 lg:mt-0">
                  <li>
                      <a href="#"
                          class="block py-2 pl-4 pr-4 lg:mx-1.5 text-white bg-purple-700 rounded lg:bg-transparent lg:text-purple-900 lg:p-0 dark:text-white"
                          aria-current="page">Beranda</a>
                  </li>
                  <li class="relative">
                      <a href="#" class="block py-2 cursor-default pl-4 pr-4 lg:mx-1.5 text-gray-400 border-b border-gray-100 hover:bg-gray-50 lg:hover:bg-transparent lg:border-0 lg:p-0 dark:text-gray-400 lg:dark:hover:text-white dark:hover:bg-gray-700 dark:hover:text-white lg:dark:hover:bg-transparent dark:border-gray-700">Programs</a>
                      <span class="absolute bg-gray-50 top-[-20px] right-[-20px] border px-2 rounded-full text-xs">Soon</span>
                  </li>
                  <li class="relative">
                      <a href="#" class="block py-2 cursor-default pl-4 pr-4 lg:mx-1.5 text-gray-400 border-b border-gray-100 hover:bg-gray-50 lg:hover:bg-transparent lg:border-0 lg:p-0 dark:text-gray-400 lg:dark:hover:text-white dark:hover:bg-gray-700 dark:hover:text-white lg:dark:hover:bg-transparent dark:border-gray-700">Tentang Kami</a>
                      <span class="absolute bg-gray-50 top-[-20px] right-[-20px] border px-2 rounded-full text-xs">Soon</span>
                  </li>
                  <li class="relative">
                      <a href="#" class="block py-2 cursor-default pl-4 pr-4 lg:mx-1.5 text-gray-400 border-b border-gray-100 hover:bg-gray-50 lg:hover:bg-transparent lg:border-0 lg:p-0 dark:text-gray-400 lg:dark:hover:text-white dark:hover:bg-gray-700 dark:hover:text-white lg:dark:hover:bg-transparent dark:border-gray-700">Blog</a>
                      <span class="absolute bg-gray-50 top-[-20px] right-[-20px] border px-2 rounded-full text-xs">Soon</span>
                  </li>
                  <li class="relative">
                      <a href="#" class="block py-2 cursor-default pl-4 pr-4 lg:mx-1.5 text-gray-400 border-b border-gray-100 hover:bg-gray-50 lg:hover:bg-transparent lg:border-0 lg:p-0 dark:text-gray-400 lg:dark:hover:text-white dark:hover:bg-gray-700 dark:hover:text-white lg:dark:hover:bg-transparent dark:border-gray-700">Hubungi Kami</a>
                      <span class="absolute bg-gray-50 top-[-20px] right-[-20px] border px-2 rounded-full text-xs">Soon</span>
                  </li>
              </ul>
          </div>
      </div>
  </nav>
</template>