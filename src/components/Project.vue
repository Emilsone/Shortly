<template>
  <section class=" text-black body-font mt-24 section-container py-6">
    <div class="text">
      <h1 class="font-bold text-3xl text-center">Advanced Statistics</h1>
      <p class="font-sm text-sm text-center">
        Track how your links are performing across the web with our advanced
        statistics dashboard.
      </p>
    </div>
    <div class="container px-5 py-24 mx-auto">
      <div class="flex flex-wrap -m-4">
        <div class="p-4 md:w-1/3">
         <div class="img-class">
              <img
                class="lg:h-12 md:h-36 w-6 sm:pt-6 pt-0 "
                src="../assets/icon-brand-recognition.png"
                alt="blog"
              />
            </div>
          <div
            class="h-1/3 border-2 border-gray-200 bg-white rounded-lg overflow-hidden"
          >
           

            <div class="p-6 pt-12">
              <!-- <h2 class="tracking-widest text-xs title-font font-medium text-gray-500 mb-1">Brand Recognition</h2> -->
              <h1 class="title-font text-2xl font-bold text-gray-900 mb-3">
                Brand Recognition
              </h1>
              <p class="leading-relaxed mb-3">
                Boost your brand recognition with each click. Generic links
                don’t mean a thing. Branded links help instil confidence in your
                content..
              </p>
            </div>
          </div>
        </div>
        <div class="p-4 md:w-1/3">
        <div class="img-class record">
              <img
                class="lg:h-12 md:h-36 w-6 sm:pt-6 pt-0  "
                src="../assets/icon-detailed-records.png"
                alt="blog"
              />
            </div>
          <div
            class="h-1/3 border-2 border-gray-200 bg-white rounded-lg overflow-hidden mt-12"
          >
            

            <div class="p-6 pt-12">
              <!-- <h2 class="tracking-widest text-xs title-font font-medium text-gray-500 mb-1">CATEGORY</h2> -->
              <h1 class="title-font text-2xl font-bold text-gray-900 mb-3">
                Detailed Records
              </h1>
              <p class="leading-relaxed mb-3">
                Gain insights into who is clicking your links. Knowing when and
                where people engage with your content helps inform better
                decisions.
              </p>
            </div>
          </div>
        </div>
        <div class="p-4 md:w-1/3">
        <div class="img-class custom">
              <img
                class="lg:h-12 md:h-36 sm:w-12 sm:pt-6 pt-0  "
                src="../assets/icon-fully-customizable.png"
                alt="customizable-icon"
              />
            </div>
          <div
            class="h-1/3 border-2 border-gray-200 bg-white rounded-lg overflow-hidden mt-24"
          >
            

            <div class="p-6 pt-12">
              <!-- <h2 class="tracking-widest text-xs title-font font-medium text-gray-500 mb-1">CATEGORY</h2> -->
              <h1 class="title-font text-2xl font-bold text-gray-900 mb-3">
                Fully Customizable
              </h1>
              <p class="leading-relaxed mb-3">
                Improve brand awareness and content discoverability through
                customizable links, supercharging audience engagement.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
<script>
export default {
  name: "Projects",
  data: () => {
    return {};
  },
};
</script>
<style scoped>
.img-class {
  position: relative;
  background-color: hsl(260, 8%, 14%);
  border-radius: 50%;
  width: 80px;
  height: 80px;
  left: 20px;
  top:30px;
}
.custom img{
  width: 30%;
  height: 30%;
}
.custom{
  position: relative;
  background-color: hsl(260, 8%, 14%);
  border-radius: 50%;
  width: 80px;
  height: 80px;
  left: 20px;
  top:120px;
}
.record {
  position: relative;
  background-color: hsl(260, 8%, 14%);
  border-radius: 50%;
  width: 80px;
  height: 80px;
  left: 20px;
  top:80px;
}
.img-class img {
  margin:auto;
  /* position: absolute; */
}
.section-container{
  background-color: hsl(0, 0%, 75%);
}
@media (max-width: 575.98px) {
  .img-class {
    padding: 30px;
    margin: auto;
    left: 0;
  }
}
@media (max-width: 768px) {
 .custom{
  position: none;
  left: 0;
  top:120px;
}
.record{
  position: none;
  left: 0;
  top:80px;
}
}


</style>
