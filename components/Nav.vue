<template>
  <div class="p-4 bg-gray-800 w-full text-gray-50 flex justify-center">
    <div class="w-8/12 flex items-center space-x-3 flex-wrap justify-center">
      <a
        href="https://github.com/uvacoder/uva-viewmygithub-4303"
        title="Developer"
        class="hover:(transition ease-in-out duration-300 text-red-600) md:text-xl text-lg font-bold"
      >View GitHub user profile data with repos</a>
      <nuxt-link to="/" class="bg-gray-700 p-2 rounded-md font-bold" v-if="$route.params.user">Go back</nuxt-link>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
</style>
