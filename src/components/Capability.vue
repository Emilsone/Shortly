<template>
  <section class="text-gray-700 body-font relative">
    <div class="lg:w-1/2 md:w-2/3 mx-auto">
      <div class="flex flex-wrap -m-2">
        <div class="p-2 w-5/6">
          <input
            class="w-full bg-gray-100 rounded border border-gray-400 focus:outline-none focus:border-indigo-500 text-base px-2 py-2"
            placeholder="Shorten a link here ......."
            type="text"
          />
        </div>
        <div class="p-2">
          <button
            class="w-full text-white bg-indigo-500 border-0 py-2 px-8 focus:outline-none hover:bg-indigo-600 rounded text-lg"
          >
            Shorten It
          </button>
        </div>
      </div>
    </div>
  </section>
</template>
<script>
export default {
  name: "Welcome",
};
</script>
<style scoped>

</style>
