<template>
  <div class="bg-gray-100 p-3 rounded-3xl main">
    <div class="flex items-center mt-4">
      <svg
        class="ml-4"
        width="24"
        height="24"
        viewBox="0 0 24 24"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
      >
        <circle
          cx="11.7666"
          cy="11.7666"
          r="8.98856"
          stroke="#6B7280"
          stroke-width="1.5"
          stroke-linecap="round"
          stroke-linejoin="round"
        />
        <path
          d="M18.0183 18.4851L21.5423 22"
          stroke="#6B7280"
          stroke-width="1.5"
          stroke-linecap="round"
          stroke-linejoin="round"
        />
      </svg>

      <input
        class="rounded-xl   placeholder-gray-500 weight outline-none pl-2 bg-transparent"
        type="text"
        placeholder="Search"
      />
    </div>
    <h1 class="mt-6 ml-5 text-3xl w-32 font-black ">
      Overview
    </h1>
    <div class="flex mt-6  flex-wrap justify-center">
      <div
        class="bg-blue-200 w-56 h-36 rounded-3xl mt-16 flex flex-col items-start "
      >
        <div class="flex">
          <div
            class="w-6 h-6 rounded-full bg-red-300 mt-4 ml-4 absolute opacity-40"
          ></div>
          <div
            class="w-6 h-6 rounded-full bg-red-300 mt-4 ml-8 absolute opacity-60"
          ></div>
        </div>
        <p class=" ml-4 mt-16 text-xl">
          **** **** **** <span class="text-base align-top">4102</span>
        </p>
      </div>
      <div
        class="bg-blue-200 w-64 h-60 rounded-3xl flex flex-col ml-4 items-start"
      ></div>
      <div
        class="bg-blue-200 w-72 h-60 rounded-3xl flex flex-col mt-4 items-start"
      ></div>
      <div
        class="bg-blue-200 w-48 h-60 rounded-3xl flex flex-col ml-4 mt-4 items-start"
      ></div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style></style>
