<template>
  <section>
    <!-- component -->
    <div class="w-full">
      <div class="h-2 bg-indigo"></div>
      <div class="flex items-center justify-center ">
        <div class="container mx-24 my-24 bg-gray-200 rounded shadow-3xl">
          <div class="px-12 py-6">
            <div class="text-center">
              <h1
                class="font-normal text-3xl text-grey-darkest leading-loose my-3 w-full"
              >
                Get our latest product
              </h1>
              <div
                class="flex lg:w-2/3 w-full sm:flex-row flex-col mx-auto px-8 sm:px-0"
              >
               
                <input
                  class="w-1/2 bg-gray-100 rounded border border-gray-400 focus:outline-none focus:border-indigo-500 text-base px-4 py-2 mr-4 mb-4 sm:mb-0"
                  placeholder="Email"
                  type="email"
                />
                <button
                  class="text-white bg-black border-0 py-2 px-8 focus:outline-none hover:bg-black rounded text-lg"
                >
                  Get
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
<script>
export default {
  name: 'Suscribe'
}
</script>
