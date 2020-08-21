<template>
  <section class="text-gray-700 body-font">
  <div class="container mx-auto flex px-5 py-24 md:flex-row flex-col items-center">
    <div class="lg:flex-grow md:w-1/2 lg:pr-24 md:pr-16 flex flex-col md:items-start md:text-left mb-16 md:mb-0 items-center text-center">
      <h1 class="title-font sm:text-4xl text-3xl mb-4 font-medium text-gray-900">More than just shorter links</h1>
      <p class="mb-8 leading-relaxed">Build your brand recognition and get detailed insights<br>on how your links are peforming</p>
      <div class="flex w-full md:justify-start justify-center">
        <button class="inline-flex text-white bg-indigo-500 border-0 py-4 px-12 focus:outline-none hover:bg-indigo-600 rounded text-lg btn">Get Started</button>
      </div>
      
    </div>
    <div class="lg:max-w-lg lg:w-full md:w-1/2 w-5/6">
      <img class="object-cover object-center rounded" alt="hero" src="https://dummyimage.com/720x600">
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
 
}
/* @media  (max-width: 755px){
  
  #love{
    font-size: 40px;
    text-align: center;
    font-weight: 700;
  }
  .lorem{
    text-align: center;
    font-size: 15px;
    padding: 10px 9px 9px 10px;
  }
  
} */
#product{
  background-color:linear-gradient(96.76deg, #4158D0 23.44%, #C850C0 56.25%, #FFCC70 89.05%);
}
.lorem{
  color: #000000;
}

</style>
