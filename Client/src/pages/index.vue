<script setup lang="ts"></script>

<template>
  <div class="bg-white">
    <div class="container col-xxl-8 px-4 py-5 fade-in">
      <div class="row flex-lg-row-reverse align-items-center g-5 py-5">
        <div class="col-lg-6">
          <h1 class="display-5 fw-bold text-body-emphasis lh-1 mb-3">
            Morning or Night, Our Coffee is Just Right!
          </h1>
          <h3>
            Get an early kickstart to your day or energize your night with our
            coffees and teas!
          </h3>
        </div>

        <div class="col-10 col-sm-8 col-lg-6">
          <img
            src="../assets/cs-6-crop.jpg"
            class="d-block mx-lg-auto img-fluid img-round"
            alt="Campfire Latte"
            width="500"
            height="500"
            loading="lazy"
          />
        </div>
      </div>
    </div>

    <div>
      <div
        id="carouselExampleInterval"
        class="carousel slide container"
        data-bs-ride="carousel"
      >
        <div class="carousel-inner">
          <div class="carousel-item active" data-bs-interval="10000">
            <img src="../assets/cs-1.jpeg" class="d-block w-100" alt="..." />
          </div>
          <div class="carousel-item" data-bs-interval="2000">
            <img src="../assets/cs-2.jpeg" class="d-block w-100" alt="..." />
          </div>
          <div class="carousel-item">
            <img src="../assets/cs-3.jpeg" class="d-block w-100" alt="..." />
          </div>
        </div>
        <button
          class="carousel-control-prev"
          type="button"
          data-bs-target="#carouselExampleInterval"
          data-bs-slide="prev"
        >
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button
          class="carousel-control-next"
          type="button"
          data-bs-target="#carouselExampleInterval"
          data-bs-slide="next"
        >
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>
    </div>

    <div class="cafe-secondary-2">
      <div class="px-4 py-5 my-5 text-center">
        <h1 class="display-5 fw-bold text-body-emphasis"></h1>
        <div class="col-lg-6 mx-auto">
          <h3 class="text-white mb-4">
            Welcome to our cozy cafe where we provide a variety of drinks from
            specialty coffees to lovely aromatic teas. We also offer baked goods
            to perfectly compliment our premium tasting drinks.
          </h3>
          <div class="d-grid gap-2 d-sm-flex justify-content-sm-center">
            <RouterLink
              to="/menu"
              type="button"
              class="btn cafe-button-2 btn-lg px-4 gap-3"
            >
              Menu
            </RouterLink>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div class="container col-xxl-8 px-4 py-5">
    <div class="row flex-lg-row-reverse align-items-center g-5 py-5">
      <div class="col-10 col-sm-8 col-lg-6">
        <img
          src="../assets/cafestock.jpg"
          class="d-block mx-lg-auto img-fluid img-round"
          alt="Cafe Stock"
          width="700"
          height="500"
          loading="lazy"
        />
      </div>
      <div class="col-lg-6">
        <h1 class="display-5 fw-bold text-body-emphasis lh-1 mb-3">
          Our Story
        </h1>
        <h3 class="mb-5">
          Morning Night Cafe was founded in 2024 by a group of students who
          shared a passion for coffee and tea.
        </h3>
        <div class="d-grid gap-2 d-sm-flex justify-content-sm-center">
          <RouterLink
            to="/about"
            type="button"
            class="btn cafe-button-1 text-white btn-lg px-4 gap-3"
          >
            Learn More
          </RouterLink>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped></style>
