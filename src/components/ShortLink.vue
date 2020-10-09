<template>
  <section class="text-gray-700 body-font relative section-link">
    <div class="lg:w-1/2 md:w-2/3 mx-auto ">
      <div class="flex flex-wrap -m-2">
        <div class="p-2 w-3/4">
        <label>
          <input
            class="w-full bg-gray-100 rounded border border-gray-400 focus:outline-none focus:border-indigo-500 text-base px-2 py-4"
            placeholder="Shorten a link here ......."
            type="text"
          />
          </label>
        </div>
        <div class="p-2">
          <button
            class="w-full text-white bg-indigo-500 border-0 py-4 px-8 focus:outline-none hover:bg-indigo-600 rounded text-lg btn"
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
.btn{
  font-size:14px;
  /* border-radius:25px; */
  background-color: #2ACFCF;
  color: #FFFFFF;
 
}
.section-link{
  padding: 45px 0px;
  background-image: url(../assets/bg-shorten-desktop.png);
  background-repeat: no-repeat;
  object-fit: cover;
  background-color: hsl(257, 27%, 26%);
  height: 23vh;
  width: 90%;
  margin: 0px 50px;
}
</style>
