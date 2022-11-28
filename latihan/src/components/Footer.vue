<template>
  <div class="py-5">
        <div class="header d-flex justify-content-center">
          <img src="./..\assets\img\logo.png" class="" alt="logo">
        </div>

        <div class="container py-5 px-5">
            <div class="row d-flex justify-content-around">
              <div class="col-2 d-flex flex-column">
                <h4>Overview</h4>
                <a href="#" class="text-dark">Shipping</a>
                <a href="#" class="text-dark">Refund</a>
                <a href="#" class="text-dark">Promotion</a>
              </div>
              <div class="col-2 d-flex flex-column">
                <h4>Company</h4>
                <a href="#" class="text-dark">About</a>
                <a href="#" class="text-dark">Career</a>
                <a href="#" class="text-dark">Contact Us</a>
              </div>
              <div class="col-2 d-flex flex-column">
                <h4>Explore</h4>
                <a href="#" class="text-dark">Terms & Conds</a>
                <a href="#" class="text-dark">Privacy Policy</a>
                <a href="#" class="text-dark">For Developer</a>
              </div>
              <div class="col-4 d-flex flex-column">
                <h4>Special Letter</h4>
                <form class="form-inline">
                    <input class="form-control mr-sm-2" type="search" placeholder="Your Email Address" aria-label="Search">
                    <button class="btn my-2 my-sm-0 bg-danger" type="submit"><img src="./..\assets\img\tele-icon.png" alt="tele-icon"></button>
                </form>
              </div>
            </div>
          </div>
      </div>
</template>

<script>
export default {
    name    : "FooterComponent"
}
</script>

<style>

</style>