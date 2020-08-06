<template>
  <div class="container">
    <!-- Header -->
    <app-header></app-header>

    <hr />

    <div class="row">
      <!-- Servers -->
      <app-servers></app-servers>
      <!-- Server Details -->
      <app-server-details></app-server-details>
    </div>

    <hr />

    <!-- Footer -->
    <app-footer></app-footer>
  </div>
</template>

<script>
import Header from "./Header";
import Servers from "./Servers";
import ServerDetails from "./ServerDetails";
import Footer from "./Footer";
export default {
  components: {
    "app-header": Header,
    "app-servers": Servers,
    "app-server-details": ServerDetails,
    "app-footer": Footer,
  },
};
</script>

<style>
</style>