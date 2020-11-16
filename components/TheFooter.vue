<template>
  <footer class="footer___bg text-white">
    <div class="container mx-auto px-8">
      <div class="w-full flex flex-col md:flex-row py-6">
        <div class="flex-1 mb-6">
          <logo />
          <p class="text-sm px-5">
            Welcome to Organik. Our products are freshly harvested, washed ready
            for box and finally delivered from our family farm right to your
            doorstep.
          </p>
        </div>

        <div class="flex-1 px-4">
          <p class="uppercase md:mb-6 font-bold">INFORMATION</p>
          <ul class="list-reset mb-6">
            <li class="mt-2 inline-block mr-2 md:block md:mr-0">
              <a
                href="#"
                class="no-underline hover:underline  hover:text-orange-500"
                >New Products</a
              >
            </li>
            <li class="mt-2 inline-block mr-2 md:block md:mr-0">
              <a
                href="#"
                class="no-underline hover:underline  hover:text-orange-500"
                >Top Sellers</a
              >
            </li>
            <li class="mt-2 inline-block mr-2 md:block md:mr-0">
              <a
                href="#"
                class="no-underline hover:underline  hover:text-orange-500"
                >Our Blog</a
              >
            </li>
            <li class="mt-2 inline-block mr-2 md:block md:mr-0">
              <a
                href="#"
                class="no-underline hover:underline  hover:text-orange-500"
                >About Our Shop</a
              >
            </li>
          </ul>
        </div>
        <div class="flex-1">
          <p class="uppercase text-gray-500 md:mb-6 font-bold">USEFUL LINKS</p>
          <ul class="list-reset mb-6">
            <li class="mt-2 inline-block mr-2 md:block md:mr-0">
              <a
                href="#"
                class="no-underline hover:underline  hover:text-orange-500"
                >FAQ</a
              >
            </li>
            <li class="mt-2 inline-block mr-2 md:block md:mr-0">
              <a
                href="#"
                class="no-underline hover:underline  hover:text-orange-500"
                >About Us</a
              >
            </li>
            <li class="mt-2 inline-block mr-2 md:block md:mr-0">
              <a
                href="#"
                class="no-underline hover:underline  hover:text-orange-500"
                >Help</a
              >
            </li>
            <li class="mt-2 inline-block mr-2 md:block md:mr-0">
              <a
                href="#"
                class="no-underline hover:underline  hover:text-orange-500"
                >Secure Shopping</a
              >
            </li>
          </ul>
        </div>

        <div class="flex-1 md:w-1/2 w-full px-4">
           <p class="uppercase text-gray-500 md:mb-6 font-bold">INFORMATION</p>
          <div
            class="flex xl:flex-no-wrap md:flex-no-wrap lg:flex-wrap flex-wrap justify-center items-end md:justify-start"
          >
            <div class="relative w-40 sm:w-auto xl:mr-4 lg:mr-0 sm:mr-4 mr-2">
              <label for="footer-field" class="leading-7 text-sm"
                >Enter your email address for our mailing list to keep yourself
                updated.</label
              >
              <input
                type="text"
                id="footer-field"
                name="footer-field"
                class="w-full bg-gray-100 border-gray-300 focus:border-indigo-500 text-base outline-none text-gray-700 py-1 px-6 leading-8 transition-colors duration-200 ease-in-out"
              />
            </div>
            <button
              class="lg:mt-2 xl:mt-0 flex-shrink-0 inline-flex text-white border-0 py-2 px-6 focus:outline-none  bg-green-600"
            >Ok
            </button>
          </div>
        </div>
      </div>
    </div>
    <div class="bg-black">
    </div>
  </footer>
</template>

<script>
import Logo from '@/components/Logo'

export default {
  name: 'TheFooter',
  components: {
    Logo
  }
}
</script>
<style>
.footer___bg{
 background-color: rgb(0, 0, 0);
 color: rgb(171, 171, 171);
}
</style>

