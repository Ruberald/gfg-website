<script setup>
import Team from '../components/Team.vue'
</script>

<template>
  <main>
    <div class="about px-4 container mx-auto">
      <div class="my-8 flex items-center justify-between md:justify-center">
        <span class="border-b-2 border-t-2 w-8 md:w-24 inline-block mr-2 rounded"></span>

        <h1 class="text-gray-800 md:text-2xl font-bold text-center">
          About us
        </h1>

        <span class="border-b-2 border-t-2 w-8 md:w-24 inline-block ml-2 rounded"></span>
      </div>
      <h1>We're an active, inspired bunch of youth etching our steps into the sand of the world at every turn! Come join us on this journey of a technically thrilling ecstasy!</h1>
    </div>
    <Team />
  </main>
</template>

<style>
/*  @media (min-width: 1024px) {
    .about {
      min-height: 100vh;
      display: flex;
      align-items: center;
    }
  }
*/</style>
