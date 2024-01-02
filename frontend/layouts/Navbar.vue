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
            </div>
      </div>
  </nav>
</template>