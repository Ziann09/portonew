<template>
  <!-- start section -->
  <section class="pb-10 md:pb-20 pt-20 md:pt-36 bg-tersier font-poppins">
    <div class="w-full relative mt-2">
      <h3 class="text-3xl md:text-4xl text-primary text-center">Eziansyah Rifki Abdillah</h3>
    </div>
  </section>
  <!-- end section -->
  <!-- start section -->
  <section class="font-poppins px-4">
    <div class="flex flex-wrap">
      <div class="w-full px-4 md:px-4 lg:w-1/2">
        <div class="mt-6 md:mt-10 flex justify-center md:justify-start">
          <img src="/self.jpg" alt="Self">
        </div>
      </div>
      <div class="w-full px-4 md:px-6 lg:w-1/2 grid mt-6 md:mt-0">
        <div class="text-xl md:text-2xl text-primary ml-0 md:ml-3 underline-offset-4 underline">
          <h2>UI/UX Designer</h2>
        </div>
        <p class="mt-2 text-sm md:text-base">
          Halo, nama saya <strong>Eziansyah Rifki Abdillah</strong>, seorang junior
          ui/ux designer web developer yang sedang bersemangat memulai karir di dunia
          pengembangan web. Saya percaya bahwa web development adalah medan yang
          menarik dan terus berkembang, dan saya sangat antusias untuk menjadi
          bagian dari komunitas ini.
        </p>
        <transition>
          <div v-show="TampilkanAboutMe">
            <p class="mt-2 text-sm md:text-base">
              Meskipun saya masih di awal karir saya, saya telah menunjukkan
              minat yang kuat dalam dunia teknologi dan telah meluangkan waktu
              untuk memperoleh pengetahuan dan keterampilan yang diperlukan
              untuk menjadi seorang UI/UX Designer dan Front - End web developer. Saya memiliki
              pemahaman yang baik tentang HTML, CSS, dan Figma sebagai
              fondasi utama dalam pengembangan web. Selain itu, saya juga
              memiliki pengetahuan tentang kerangka kerja seperti Vue.js dan
              Django.
            </p>
            <p class="mt-2 text-sm md:text-base">
              Saya sangat berharap untuk mendapatkan kesempatan untuk belajar
              dan tumbuh bersama tim yang berpengalaman dalam perusahaan ini.
              Saya siap menghadapi tantangan dan berkontribusi secara positif
              dalam pengembangan proyek-proyek yang menarik. Saya juga sangat
              antusias untuk terus meningkatkan keterampilan saya dan menjadi
              seorang profesional web developer yang handal.
            </p>
            <p class="mt-2 text-sm md:text-base">
              Terima kasih telah meluangkan waktu untuk membaca "About" saya.
              Saya berharap dapat bertemu dengan Anda dan membahas lebih lanjut
              tentang bagaimana saya dapat berkontribusi dalam tim Anda.
            </p>
          </div>
        </transition>
        <a @click="TampilkanLebihBanyak = !TampilkanLebihBanyak" class="cursor-pointer font-bold underline text-sm md:text-base mt-2">
          <p v-if="TampilkanLebihBanyak" @click="TampilkanAboutMe = !TampilkanAboutMe">
            Tampilkan Lebih Banyak ...
          </p>
          <p v-else @click="TampilkanAboutMe = !TampilkanAboutMe">
            Tampilkan Lebih Sedikit...
          </p>
        </a>
      </div>
    </div>
  </section>
  <!-- end section -->
  <!-- start section -->
  <section class="font-poppins mt-8 md:mt-12">
    <div class="flex flex-wrap justify-center mx-4 rounded-3xl py-4 md:py-6">
      <div class="w-full relative px-3">
        <h2 class="font-poppins text-slate-600 text-center text-2xl md:text-3xl">
          Tech Stack
        </h2>
        <div class="flex flex-wrap justify-center mt-4 md:mt-6 container px-3">
              <img src="/tech/html.png" alt="" class="w-[50px] md:w-[70px] mx-2 md:mx-3 my-2" />
              <img src="/tech/css.png" alt="" class="w-[50px] md:w-[70px] mx-2 md:mx-3 my-2" />
              <img src="/tech/vue.png" alt="" class="w-[50px] md:w-[70px] mx-2 md:mx-3 my-2" />
              <img src="/tech/php.png" alt="" class="h-[40px] md:h-[50px] mx-2 md:mx-3 my-2" />
              <img src="/tech/sql.png" alt="" class="h-[40px] md:h-[50px] mx-2 md:mx-3 my-2" />
              <img src="/tech/laravel.png" alt="" class="h-[40px] md:h-[50px] mx-2 md:mx-3 my-2" />
              <img src="/tech/node.png" alt="" class="h-[40px] md:h-[50px] mx-2 md:mx-3 my-2" />
              <img src="/tech/django.png" alt="" class="w-[120px] md:w-[150px] mx-2 md:mx-3 my-2" />
        </div>
      </div>
    </div>
  </section>
  <!-- end section -->
  <!-- start section -->
  <section class="font-poppins mt-4 md:mt-8">
    <div class="flex flex-wrap">
      <div class="w-full px-4 md:px-6 lg:w-1/2 grid">
        <div class="mt-4 text-xl md:text-2xl text-primary ml-2 md:ml-6 underline-offset-4 underline">
          <h2>Pendidikan</h2>
        </div>
        <div class="mx-2 md:mx-6">
          <ul class="list-disc">
            <li>
              <h2 class="mt-3 md:mt-4 text-xl md:text-2xl text-primary ml-4 md:ml-6 font-bold">
                Formal
              </h2>
              <ul class="list-decimal mx-4 md:mx-6">
                <li>
                  <h3 class="text-lg md:text-xl text-primary opacity-90">
                    SDS Nugraha
                  </h3>
                  <p class="italic text-sm md:text-base text-primary opacity-80">2022 - 2025</p>
                </li>
              </ul>
              <ul class="list-decimal mx-4 md:mx-6">
                <li>
                  <h3 class="text-lg md:text-xl text-primary opacity-90">
                    SIK Al - Fatwa
                  </h3>
                  <p class="italic text-sm md:text-base text-primary opacity-80">2022 - 2025</p>
                </li>
              </ul>
              <ul class="list-decimal mx-4 md:mx-6">
                <li>
                  <h3 class="text-lg md:text-xl text-primary opacity-90">
                    SMKN 4 Bandung (RPL)
                  </h3>
                  <p class="italic text-sm md:text-base text-primary opacity-80">2022 - 2025</p>
                </li>
              </ul>
            </li>
          </ul>
        </div>
      </div>
      <div class="w-full px-4 lg:w-1/2 flex justify-center">
        <div class="mt-6 md:mt-10">
          <img src="/ilustrasi/School-bro.svg" alt="coding ilustrasi" class="bg-transparent w-3/4 md:w-auto max-w-full" />
        </div>
      </div>
    </div>
  </section>
  <!-- end section -->
</template>

<script lang="ts" setup>
import { ref } from "vue";
const TampilkanAboutMe = ref(false);
const TampilkanLebihBanyak = ref(true);
</script>

<style>
/* Import Poppins font */
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap');

/* we will explain what these classes do next! */
.v-enter-active,
.v-leave-active {
  transition: opacity 0.5s ease;
}

.v-enter-from,
.v-leave-to {
  opacity: 0;
}

.custom {
  background-image: url(/ilustrasi/bg-nature.jpg);
}

/* Add Poppins as default font */
:root {
  font-family: 'Poppins', sans-serif;
}

.profile-image {
  border-radius: 12px; /* Adds rounded corners */
  max-width: 400px; /* Prevents image from becoming too large */
  height: auto; /* Maintains aspect ratio */
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); /* Subtle shadow for depth */
  transition: transform 0.2s ease; /* Smooth hover effect */
}

.profile-image:hover {
  transform: scale(1.02); /* Slight zoom on hover */
}

/* Media queries for responsive design */
@media (max-width: 768px) {
  .profile-image {
    margin-left: 0;
    max-width: 100%;
  }
}
</style>