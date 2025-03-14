<template>
  <!-- hero section -->
  <section class="pb-5 bg-gradient-to-b from-primary">
    <div class="flex flex-wrap justify-center align-middle p-0 w-full h-screen mb-12" onload="lazy">
      <div class="self-center text-center">
        <h1 class="text-dark font-semibold text-4xl lg:text-6xl">PROJECT.</h1>
        <h2 class="font-medium text-primary text-lg mb-5 lg:text-2xl mt-5">
          kumpulan <span class="text-dark"> project </span> yang sudah saya buat
        </h2>
      </div>
    </div>
  </section>
  <!-- end hero section -->

  <!-- start section -->
  <section class="bg-fixed bg-center bg-cover custom py-6">
    <div class="grid grid-cols-3 gap-4 mx-2">
      <div class="grid-fun group">
        <img src="/project1.png" alt="Project Image" />
        <span
          class="absolute font-mono z-100 text-center opacity-0 text-white group-hover:opacity-80 ease-in"
        >
          <h1 class="text-2xl font-bold">Done</h1>
          <p class="text-base">pengerjaan dari September - Oktober 2024</p>
        </span>
      </div>
      <div class="grid-fun group">
        <img src="/project2.png" alt="Project Image" />
        <span
          class="absolute font-mono z-100 text-center opacity-0 text-white group-hover:opacity-80 ease-in"
        >
          <h1 class="text-2xl font-bold">Done</h1>
          <p class="text-base">pengerjaan dari Agustus - September 2024</p>
        </span>
      </div>
      <div class="grid-fun group">
        <img src="/project3.png" alt="Project Image" />
        <span
          class="absolute font-mono z-100 text-center opacity-0 text-white group-hover:opacity-80 ease-in"
        >
          <h1 class="text-2xl font-bold">Done</h1>
          <p class="text-base">pengerjaan dari Agustus - September 2024</p>
        </span>
      </div>
      <div class="col-span-2 grid-fun group">
        <img src="/project4.png" alt="Project Image" />
        <span
          class="absolute font-mono z-100 text-center opacity-0 text-white group-hover:opacity-80 ease-in"
        >
          <h1 class="text-2xl font-bold">Done</h1>
          <p class="text-base">pengerjaan dari Februari - Juni 2024</p>
        </span>
      </div>
      <div class="grid-fun group">
        <img src="/project5.png" alt="Project Image" />
        <span
          class="absolute font-mono z-100 text-center opacity-0 text-white group-hover:opacity-80 ease-in"
        >
          <h1 class="text-2xl font-bold">Coming Soon</h1>
          <p class="text-base">pengerjaan dari Januari - Now 2025</p>
        </span>
      </div>
    </div>
  </section>
  <!-- end section -->
</template>

<style>
.custom {
  background-image: url(/ilustrasi/bg-nature.jpg);
}
</style>
