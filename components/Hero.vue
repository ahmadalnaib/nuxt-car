<template>
  <div
    class="relative h-screen w-100 bg-no-repeat bg-cover bg-bottom bg-[url('/public/img/bg.webp')]"
  >
    <div class="z-10 absolute w-full h-full flex justify-center items-center">
      <div class="text-center w-1/2">
        <h1 class="text-8xl font-serif mb-10 text-white">Find your drive</h1>
        <div
          class="font-serif w-[100p0x] text-2xl rounded-full bg-white flex justify-between overflow-hidden drop-shadow-2xl mx-auto"
        >
          <input
            class="py-3 px-5 w-full text-2xl rounded-full focus:outline-none"
            type="text"
            placeholder="Search by city"
          />
          <button class="w-[20%] bg-green-900 text-white p-2">Search</button>
        </div>
      </div>
    </div>

    <div class="z-1 absolute w-full h-full bg-black opacity-50"></div>
  </div>
</template>
