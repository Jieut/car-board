<template>
  <div
    class="body-bg min-h-screen pt-12 md:pt-20 pb-6 px-2 md:px-0"
    style="font-family: 'Lato', sans-serif"
  >
    <header class="max-w-lg mx-auto">
      <a href="#">
        <h1 class="text-4xl font-bold text-white text-center">ECS Solution.</h1>
      </a>
    </header>

    <main
      class="bg-white max-w-lg mx-auto p-8 md:p-12 my-10 rounded-lg shadow-2xl"
    >
      <section>
        <h3 class="font-bold text-2xl">Welcome to ECS</h3>
        <p class="text-gray-600 pt-2">Sign in to your account.</p>
      </section>

      <section class="mt-10">
        <div class="flex flex-col">
          <div class="mb-6 pt-3 rounded bg-gray-200">
            <label
              class="block text-gray-700 text-sm font-bold mb-2 ml-3"
              for="email"
              >Email</label
            >
            <input
              type="text"
              id="email"
              class="bg-gray-200 rounded w-full text-gray-700 focus:outline-none border-b-4 border-gray-300 focus:border-purple-600 transition duration-500 px-3 pb-3"
              placeholder="your@email.com"
            />
          </div>
          <div class="mb-6 pt-3 rounded bg-gray-200">
            <label
              class="block text-gray-700 text-sm font-bold mb-2 ml-3"
              for="password"
              >Password</label
            >
            <input
              type="password"
              id="password"
              class="bg-gray-200 rounded w-full text-gray-700 focus:outline-none border-b-4 border-gray-300 focus:border-purple-600 transition duration-500 px-3 pb-3"
              placeholder="Password"
            />
          </div>
          <div class="flex justify-end">
            <a
              href="#"
              class="text-sm text-purple-600 hover:text-purple-700 hover:underline mb-6"
              >Forgot your password?</a
            >
          </div>
          <input
            class="bg-purple-600 hover:bg-purple-700 text-white font-bold py-2 rounded shadow-lg hover:shadow-xl transition duration-200"
            type="button"
            value="Sign In"
          />
        </div>
      </section>
    </main>

    <div class="max-w-lg mx-auto text-center mt-12 mb-6">
      <p class="text-white">
        Don't have an account?
        <a href="#" class="font-bold hover:underline">Sign up</a>.
      </p>
    </div>

    <footer class="max-w-lg mx-auto flex justify-center text-white">
      <a href="#" class="hover:underline">Contact</a>
      <span class="mx-3">•</span>
      <a href="#" class="hover:underline">Privacy</a>
    </footer>
  </div>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  name: "App",
});
</script>

<style>
.body-bg {
  background-color: #9921e8;
  background-image: linear-gradient(315deg, #9921e8 0%, #5f72be 74%);
}
</style>
