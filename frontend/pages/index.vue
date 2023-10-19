<script setup></script>

<template>
  <Html lang="en">
    <Head>
      <Title>Organisasi Ngoding Bareng</Title>
      <Meta name="description" :content="`My page's ${number} description`" />
    </Head>
  </Html>

  <div>
    <nav class="text-3xl font-bold underline bg-gray-200">
      <div
        class="container d-flex flex-column flex-md-row justify-content-between"
      >
        <a class="py-2" href="/"> Logo </a>
        <a class="py-2 d-none d-md-inline-block" href="#">Coming Soon</a>
      </div>
    </nav>

    <div
      class="position-relative overflow-hidden p-3 p-md-5 m-md-3 text-center bg-light"
    >
      <div class="col-md-6 p-lg-5 mx-auto my-5">
        <h1 class="display-4 font-weight-normal">Ngobar Site</h1>
        <p class="lead font-weight-normal">
          Website masih pengembangan, kuy kita
          <span class="text-decoration-underline">#joinajadulu</span>, join
          discordnya bisa klik tombol dibawah ini.
        </p>
        <a
          class="btn btn-outline-secondary"
          href="https://discord.gg/d9QSkAjgVV"
          >Gabung Discord</a
        >
      </div>
      <div class="product-device box-shadow d-none d-md-block"></div>
      <div
        class="product-device product-device-2 box-shadow d-none d-md-block"
      ></div>
    </div>

    <footer class="container py-5">
      <div class="row">
        <div class="col-12 col-md">
          Logo
          <small class="d-block mb-3 text-muted">&copy; 2023</small>
        </div>
        <div class="col-6 col-md">
          <h5>Menu</h5>
          <ul class="list-unstyled text-small">
            <li><a class="text-muted" href="/">Home</a></li>
            <li><a class="text-muted" href="#">Coming Soon</a></li>
            <li><a class="text-muted" href="#">Coming Soon</a></li>
            <li><a class="text-muted" href="#">Coming Soon</a></li>
            <li><a class="text-muted" href="#">Coming Soon</a></li>
            <li><a class="text-muted" href="#">Coming Soon</a></li>
          </ul>
        </div>
        <div class="col-6 col-md">
          <h5>Contact Us</h5>
          <ul class="list-unstyled text-small">
            <li>
              Email: <a class="text-muted" href="#">ngobarpamulang@gmail.com</a>
            </li>
            <li>
              Discord:
              <a class="text-muted" href="#">https://discord.gg/d9QSkAjgVV</a>
            </li>
          </ul>
        </div>
      </div>
    </footer>
  </div>
</template>
