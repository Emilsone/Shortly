<template>
  <section class="text-gray-700 body-font">
  <div class="container mx-auto flex px-5 py-24 md:flex-row flex-col items-center">
    <div class="lg:flex-grow md:w-1/2 lg:pr-24 md:pr-16 flex flex-col md:items-start md:text-left mb-16 md:mb-0 items-center text-center">
      <h1 class="title-font sm:text-4xl text-3xl mb-4 font-bold text-gray-900">More than just shorter links</h1>
      <p class="mb-8 leading-relaxed">Build your brand recognition and get detailed insights<br>on how your links are peforming</p>
      <div class="flex w-full md:justify-start justify-center">
        <button class="inline-flex text-white bg-indigo-500 border-0 py-4 px-12 focus:outline-none hover:bg-indigo-600 rounded text-lg btn">Get Started</button>
      </div>
      
    </div>
    <div class="lg:max-w-lg lg:w-full md:w-1/2 w-5/6">
      <img class="object-cover object-center rounded" alt="illustration of lady working" src="../assets/illustration-working.png">
    </div>
  </div>
</section>
</template>
<script>
export default {
  name: "Banner",
};
</script>
<style scoped>
.section {
background-color:white;
}
h1 {
  font-size: 72px;
  font-weight:800;
}
.btn{
  font-size:14px;
  border-radius:25px;
  background-color: #2ACFCF;
  color: #FFFFFF;
 
}

</style>
