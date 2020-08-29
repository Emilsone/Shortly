<template>
  <section class=" section-contact text-center ">
    <div class="contact-me py-12">
      <h1 class="text-4xl text-center font-bold py-2 pt-4">
     Boost your links today
      </h1>
      <button class=" w-42 h-12   py-2 px-8 my-6 mx-4 inline-flex items-center button">
        Get Started
      </button>
    </div>
  </section>
</template>
<script>
export default {
  name: "Contact",
};
</script>
<style>
.button {
  background-color:#2ACFCF;
  border-radius: 40px;
  border: 2px solid #2ACFCF;
}
.section-contact{
  background-image: url(../assets/bg-boost-desktop.png);
  background-repeat: no-repeat;
  object-fit: cover;
  background-color: hsl(257, 27%, 26%);
  height: 35vh;
  width: 100%;
  color: white;
  /* margin: 0px 50px; */
}
</style>
