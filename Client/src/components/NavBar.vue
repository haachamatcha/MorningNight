<script setup lang="ts"></script>

<template>
  <nav class="navbar navbar-expand-lg cafe-main-1">
    <div class="container-fluid">
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarNav"
        aria-controls="navbarNav"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div
        class="collapse navbar-collapse justify-content-center"
        id="navbarNav"
      >
        <ul class="navbar-nav">
          <li class="nav-item">
            <h4 class="mt-2">
              <RouterLink to="/" class="nav-link text-black">Home</RouterLink>
            </h4>
          </li>
          <li class="nav-item">
            <h4 class="mt-2">
              <RouterLink class="nav-link text-black" to="/menu"
                >Menu</RouterLink
              >
            </h4>
          </li>
          <li>
            <RouterLink to="/" class="nav-link text-black">
              <img src="../assets/logo.png" alt="logo" width="50" height="50"
            /></RouterLink>
          </li>
          <li class="nav-item">
            <h4 class="mt-2">
              <RouterLink class="nav-link text-black" to="/about"
                >About</RouterLink
              >
            </h4>
          </li>

          <li class="nav-item">
            <h4 class="mt-2">
              <RouterLink class="nav-link text-black" to="/contact"
                >Contact</RouterLink
              >
            </h4>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<style scoped></style>
