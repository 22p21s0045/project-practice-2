<script setup>
import Navbar from "./components/Navbar.vue";
</script>

<template>
  <Navbar />
  <div alt="container" class="flex justify-center flex-col">
    <p class="text-gray-500 m-auto">
      An AI tool made for conversion rate optimization
    </p>

    <p class="m-auto p-5 text-4xl font-bold">Increase your</p>
    <p class="m-auto text-4xl bg-clip font-bold">
      conversion rate
      <span
        class="font-bold"
        style="
          background: linear-gradient(
            92deg,
            #ff00b8 67.57%,
            #004bdd 89.21%,
            #8f00ff 109.27%
          );
          background-clip: text;
          -webkit-background-clip: text;
          -webkit-text-fill-color: transparent;
        "
        >using AI</span
      >
    </p>
    <button class="bg-black w-56 m-auto text-white rounded h-12 my-7">
      Create account
    </button>

    <p class="m-auto text-gray-500">
      30 Days free trial | No credit card required
    </p>
    <img
      src="./assets/sm-dashboard.jpg"
      alt="sm-bg"
      class="m-auto my-4 rounded lg:hidden"
    />
    <img
      src="./assets/lg-dashboard.jpg"
      class="hidden lg:block m-auto my-4 rounded"
      alt=""
    />
  </div>
</template>

<style scoped>
</style>
