<template>
  <section class="hero___content">
    <div class="pt-24">
      <div
        class="container px-3 mx-auto flex flex-wrap flex-col md:flex-row items-center"
      >
        <!--Left Col-->
        <div
          class="flex flex-col w-full md:w-2/5 justify-center lg:items-start items-center text-center md:text-left"
        >
          <p class="uppercase w-full">Looking for Good furnitures?</p>
          <h1 class="my-4 text-5xl font-bold leading-tight">
            Shopnik. No #1 Trusted Furniture Website
          </h1>
          <p class="leading-normal text-lg mb-8">
            Coming soon to your door with a huge discount
          </p>

          <a href="#" class=" bg-black p-4 text-white">Shop Now</a>

          <p class="pt-24">Back | Next</p>
        </div>
        <!--Right Col-->
        <div class="w-full md:w-3/5 py-6 text-center">
          <img class="w-full md:w-4/5 z-50" src="~/assets/img/hero-img.png" alt />
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Hero'
}
</script>
