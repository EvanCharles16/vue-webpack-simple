<template>
  <div class="container">
    <!-- Header -->
    <app-header></app-header>

    <hr />

    <div class="row">
      <!-- Servers -->
      <app-servers></app-servers>
      <!-- <Servers /> -->

      <!-- Server Details -->
      <app-server-details></app-server-details>
    </div>

    <hr />

    <!-- Footer -->
    <app-footer></app-footer>
  </div>
</template>

<script>
import Header from "./components/Shared/Header";
import Servers from "./components/Server/Servers";
import ServerDetails from "./components/Server/ServerDetails";
import Footer from "./components/Shared/Footer";
export default {
  components: {
    // appHeader: Header,
    "app-header": Header,
    "app-servers": Servers,
    // Servers,
    "app-server-details": ServerDetails,
    "app-footer": Footer,
  },
};
</script>

<style>
</style>