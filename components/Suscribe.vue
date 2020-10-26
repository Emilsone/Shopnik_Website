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
              <div class="w-full text-center">
                <form action="#">
                  <div class="max-w-sm mx-auto p-1 pr-0 flex items-center">
                    <input
                      type="email"
                      placeholder="lawsonezekiel@example.com"
                      class="flex-1 appearance-none rounded shadow p-3 text-grey-dark mr-2 focus:outline-none"
                    />
                    <button
                      type="submit"
                      class="appearance-none bg-black text-white text-base font-semibold tracking-wide uppercase p-3 rounded shadow hover:bg-indigo-light"
                    >
                      Get started
                    </button>
                  </div>
                </form>
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
