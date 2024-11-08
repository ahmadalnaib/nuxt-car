<template>
  <div
    class="mx-auto mt-4 max-w-7xl space-y-4 px-4 xs:px-8 sm:px-10 lg:px-16 pb-16 w-3/5"
  >
    <div class="mt-32 flex">
      <div class="shadow border w-64 mr-10 z-30 h-[190px]">
        <div class="p-5 flex justify-between relative cursor-pointer border-b">
          <h3>Location</h3>
          <h3 class="text-green-500 capitalize">Toronto</h3>
          <!-- <div class="absolute border shadow left-56 p-5 top-1 -m-1 bg-white">
                <input type="text" class="border p-1 rounded">
                <button class="bg-green-600 w-full mt-2 rounded text-white p-1">Apply</button>
            </div> -->
        </div>
        <div class="p-5 flex justify-between relative cursor-pointer border-b">
          <h3>Make</h3>
          <h3 class="text-green-500 capitalize">Toyota</h3>
          <!-- <div class="absolute border shadow left-56 p-5 top-1 -m-1 bg-white">
                <input type="text" class="border p-1 rounded">
                <button class="bg-green-600 w-full mt-2 rounded text-white p-1">Apply</button>
            </div> -->
        </div>
        <div class="p-5 flex justify-between relative cursor-pointer border-b">
          <h3>Price</h3>
          <h3 class="text-green-500 capitalize">Any</h3>
          <!-- <div class="absolute border shadow left-56 p-5 top-1 -m-1 bg-white">
                <input type="text" class="border p-1 rounded">
                <button class="bg-green-600 w-full mt-2 rounded text-white p-1">Apply</button>
            </div> -->
        </div>
      </div>
      <div class="w-full">
        <CarCard />
      </div>
    </div>
  </div>
</template>
