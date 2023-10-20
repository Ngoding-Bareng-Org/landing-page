<script>
export default {
  name: 'Footer'
}
</script>

<template>
  <footer class="bg-slate-100">
    <div
      class="mx-auto max-w-screen-xl space-y-8 px-4 py-12 sm:px-6 lg:space-y-16 lg:px-8"
    >
      <div class="grid grid-cols-1 gap-8 lg:grid-cols-3">
        <div>
          <div class="text-teal-600">
            <img src="~/assets/images/logo/primary-logo.png" alt="" class="w-2/6">
          </div>

          <p class="mt-4 max-w-xs text-gray-500">
            Dicoding SpaceJl. Batik Kumeli No.50, Sukaluyu,Kec. Cibeunying Kaler, Kota BandungJawa Barat 40123
          </p>

          <ul class="mt-8 flex gap-6">
            <li>
              <a href="https://discord.gg/zuYkajb6ez" target="_blank">
                <i class="ri-discord-fill text-2xl"></i>
              </a>
            </li>
            <li>
              <a href="https://github.com/Ngoding-Bareng-Org" target="_blank">
                <i class="ri-github-fill text-2xl"></i>
              </a>
            </li>
            <li>
              <a href="#">
                <i class="ri-instagram-fill text-2xl"></i>
              </a>
            </li>
            <li>
              <a href="https://www.tiktok.com/@ngobarcampu" target="_blank">
                <i class="ri-tiktok-fill text-2xl"></i>
              </a>
            </li>
            <li>
              <a href="https://www.youtube.com/@ngobaracademy" target="_blank">
                <i class="ri-youtube-fill text-2xl"></i>
              </a>
            </li>
          </ul>
        </div>

        <div
          class="grid grid-cols-1 gap-8 sm:grid-cols-2 lg:col-span-2 lg:grid-cols-4"
        >
          <div>
            <p class="font-medium text-gray-900">Company</p>

            <ul class="mt-6 space-y-4 text-base">
              <li>
                <a href="#" class="text-slate-500 transition hover:opacity-75">
                  Beranda
                </a>
              </li>

              <li>
                <a href="#" class="text-slate-500 transition hover:opacity-75">
                  Tentang Kami
                </a>
              </li>

              <li>
                <a href="#" class="text-slate-500 transition hover:opacity-75">
                  Blog
                </a>
              </li>

              <li>
                <a href="#" class="text-slate-500 transition hover:opacity-75">
                  Hubungi Kami
                </a>
              </li>

            </ul>
          </div>

          <div>
            <p class="font-medium text-gray-900">Programs</p>

            <ul class="mt-6 space-y-4 text-base">
              <li>
                <a href="#" class="text-slate-500 transition hover:opacity-75">
                  Sharing Session
                </a>
              </li>

              <li>
                <a href="#" class="text-slate-500 transition hover:opacity-75">
                  CodeSynergy
                </a>
              </li>

            </ul>
          </div>

          <div>
            <p class="font-medium text-gray-900">Campus Partner</p>

            <ul class="mt-6 flex">
              <li class="me-4">
                <img src="~/assets/images/schools/unpam-logo.png" alt="Unpam Logo" class="w-50">
              </li>
              <li class="me-4">
                <img src="~/assets/images/schools/mercu-logo.png" alt="Unpam Logo" class="w-50">
              </li>
            </ul>
          </div>
        </div>
      </div>
      <div class="flex justify-between border-t pt-10">
        <p class="text-slate-400">
          Copyright © 2023 Ngobar. All Rights Reserved
        </p>

        <ul class="flex">
          <li class="ms-5">
            <a href="#" class="text-slate-400">Terms</a>
          </li>
          <li class="ms-5">
            <a href="#" class="text-slate-400">Privacy</a>
          </li>
        </ul>
      </div>
    </div>
  </footer>
</template>