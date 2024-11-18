<script setup lang="ts"></script>

<template>
  <div class="container fade-in">
    <h1 class="text-center mt-2">Contact</h1>
    <div class="row align-items-center">
      <div class="col mb-4">
        <h2 class="text-center">Get in Touch</h2>

        <div class="text-center">
          <h4>morningnightcafe@gmail.com</h4>
          <h4>(845)-555-8789</h4>
        </div>

        <div class="text-center">
          <h2 class="text-center mb-4">Visit Us</h2>
          <h4>1000 Main Street, New Paltz, NY 12561</h4>
        </div>

        <div class="text-center">
          <h2>Hours of Operation</h2>
          <h4>Sunday - 7:00 AM - 11:00 PM</h4>
          <h4>Monday - 7:00 AM - 11:00 PM</h4>
          <h4>Tuesday - 7:00 AM - 11:00 PM</h4>
          <h4>Wednesday - 7:00 AM - 11:00 PM</h4>
          <h4>Thursday - 7:00 AM - 11:00 PM</h4>
          <h4>Friday - 7:00 AM - 11:00 PM</h4>
          <h4>Saturday - 7:00 AM - 11:00 PM</h4>
        </div>
      </div>

      <div class="col text-center mb-4">
        <iframe
          src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d47628.01210659309!2d-74.12058706595543!3d41.74746864135911!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x89dd1884bdee8f8d%3A0x82c17e4b65e32b6f!2sNew%20Paltz%2C%20NY%2012561!5e0!3m2!1sen!2sus!4v1731440367603!5m2!1sen!2sus"
          width="600"
          height="450"
          style="border: 0"
          allowfullscreen="true"
          loading="lazy"
          referrerpolicy="no-referrer-when-downgrade"
        ></iframe>
      </div>
    </div>

    <div class="row center-forced">
      <h2 class="text-center">Contact Form</h2>
      <form class="col">
        <div class="mb-3">
          <label for="name" class="form-label">Name</label>
          <input type="text" class="form-control" id="name" />
        </div>
        <div class="mb-3">
          <label for="email" class="form-label">Email</label>
          <input type="email" class="form-control" id="email" />
        </div>
        <div class="mb-3">
          <label for="message" class="form-label">Message</label>
          <textarea class="form-control" id="message" rows="3"></textarea>
        </div>
        <button type="submit" class="btn cafe-button-2 mb-4">Submit</button>
      </form>
    </div>
  </div>
</template>

<style scoped>
.center-forced {
  margin: auto;
  width: 50%;
}
</style>
