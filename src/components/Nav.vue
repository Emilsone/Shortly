<template>
  <header
    class="lg:px-16 px-6 bg-white flex flex-wrap items-center lg:py-0 py-4 mt-2"
  >
    <div class="flex-1 flex justify-between items-center">
      <a href="#">
        <h1 class=" text-2xl font-medium text-gray-900">Shortly</h1>
        <!-- <img src="../assets/logo.png" alt=" love logo" class="mr-8 " /> -->
        
      </a>
    </div>

    <label for="menu-toggle" class="pointer-cursor lg:hidden block"
      ><svg
        class="fill-current text-gray-900"
        xmlns="http://www.w3.org/2000/svg"
        width="20"
        height="20"
        viewBox="0 0 20 20"
      >
        <title>menu</title>
        <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"></path></svg
    ></label>
    <input class="hidden" type="checkbox" id="menu-toggle" />

    <div class="hidden lg:flex lg:items-center lg:w-auto w-full" id="menu">
      <nav>
        <ul
          class="lg:flex items-center justify-between text-base  pt-4 lg:pt-0"
        >
          <li>
            <a
              class="lg:p-4 py-3 px-0 block border-b-2 border-transparent "
              href="#"
              > Features
            </a>
          </li>
          <li>
            <a
              class="lg:p-4 py-3 px-0 block border-b-2 border-transparent "
              href="#"
              >Pricing</a
            >
          </li>
          <li>
            <a
              class="lg:p-4 py-4 px-0 block border-b-2 border-transparent "
              href="#"
              >Resources</a
            >
          </li>
          
         <button class="inline-flex items-center bg-gray-200  border-0 py-2 px-6 focus:outline-none hover:bg-gray-300  rounded-xl text-base mt-4 md:mt-0 btn" >Sign Up
       
    </button>
        </ul>
      </nav>
    </div>
  
  </header>
</template>

<script>
export default {
  name: "Nav",
};
</script>
<style scoped>
#menu-toggle:checked + #menu {
  display: block;
}
.btn{
  font-size:14px;
  border-radius:25px;
  background-color: #2ACFCF;
  color: #FFFFFF;
 
}

</style>
