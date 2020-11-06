<template>
  <div
    class="container px-5 py-6 mx-auto flex items-center sm:flex-row flex-col"
  >
    <a
      class="flex title-font font-medium items-center md:justify-start justify-center text-gray-900"
    >
      <svg
        xmlns="http://www.w3.org/2000/svg"
        fill="none"
        stroke="currentColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="2"
        class="w-10 h-10 text-white p-2 bg-indigo-500 rounded-full"
        viewBox="0 0 24 24"
      >
        <path
          d="M12 2L2 7l10 5 10-5-10-5zM2 17l10 5 10-5M2 12l10 5 10-5"
        ></path>
      </svg>
      <span class="ml-3 text-xl">Shopnik</span>
    </a>
    <p class="text-sm text-gray-500 sm:ml-6 sm:mt-0 mt-4">
      © 2020 shopnick
    </p>
    <span
      class="inline-flex sm:ml-auto sm:mt-0 mt-4 justify-center sm:justify-start"
    >
      <img class="w-full md:w-4/5 z-50" src="~/assets/img/payment.png" alt />
    </span>
  </div>
</template>
<script>
export default {
	name:'Footerpayment'
}
</script>

