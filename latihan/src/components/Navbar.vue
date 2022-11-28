<template>
  <nav class="navbar navbar-expand-lg  px-5 py-3">
        <img src="./..\assets\img\logo.png" alt="logo">
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav ml-auto">
            <li class="nav-item">
              <a class="nav-link text-dark" href="#">Showcase</a>
            </li>
            <li class="nav-item">
              <a class="nav-link text-dark" href="#">Catalog</a>
            </li>
            <li class="nav-item">
              <a class="nav-link text-dark" href="#">Delivery</a>
            </li>
            <li class="nav-item">
                <a class="nav-link text-dark" href="#">Rewards</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#"><img src="./..\assets\img\cart-icon.png" alt="keranjang"></a>
            </li>
          </ul>
        </div>
      </nav>
</template>

<script>
export default {
    name    : "NavbarComponent"
}
</script>

<style>

</style>