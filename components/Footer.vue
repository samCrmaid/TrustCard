<template>
  <footer class="mt-32 mx-4 flex flex-col">
    <div class="flex flex-col justify-center items-center">
      <div
        class="logo w-12"
        v-html="require(`~/assets/icons/logo.svg?include`)"
      ></div>
      <!-- <p class="font-extrabold leading-tight">
        Digital&nbsp;Business&nbsp;Card
        <br />
        Generator
      </p> -->
      <p class="font-extrabold text-xl mt-2 leading-tight">TrustCard</p>
    </div>
    <p class="mt-6 text-center text-gray-400">
      Copyright &copy; 2025

      <NuxtLink
        to="/"
        class="underline text-emerald-600 font-extrabold hover:text-emerald-500 focus:text-emerald-500 transition-colors duration-200"
        >TrustCard
      </NuxtLink>
    </p>
    <p class="mt-1 mb-8 text-center text-xs text-gray-400">
      <a
        class="underline text-emerald-600 font-extrabold hover:text-emerald-500 focus:text-emerald-500 transition-colors duration-200"
        href="https://github.com/CRM-Aid/TrustCard"
        target="_blank"
        rel="noopener noreferrer"
        >View&nbsp;Source</a
      >
      | AGPLv3 License
    </p>
  </footer>
</template>

<script>
export default {}
</script>

<style></style>
