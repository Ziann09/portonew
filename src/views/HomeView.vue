<template>
    <!-- hero section -->
    <section class="mt-[50px] pb-5 bg-tersier">
        <div class="flex flex-wrap justify-center align-middle p-0 w-full h-screen mb-12 bg-fixed bg-center bg-cover custom"
            onload="lazy">
            <div class="self-center text-center">
                <h1 class="text-base text-dark font-semibold md:text-xl">
                    Halo, Saya
                    <span class="block text-white font-bold text-4xl lg:text-5xl mt-10">
                        Eziansyah Rifki Abdillah
                    </span>
                </h1>
                <h2 class="font-medium text-primary text-lg mb-5 lg:text-2xl mt-5">
                    Web Developer
                    <span class=" text-dark">
                        UI/UX Designer
                    </span>
                </h2>
                <a href=" https://api.whatsapp.com/send?phone=6288971046377&text=halo%20selamat%20siang%20saya%20tertarik%20dengan%20produk%20website%20bapak."
                    class="text-base font-semibold text-white bg-primary py-3 px-8 rounded-full hover:shadow-lg hover:opacity-80 transition duration-300 ease-in-out mt-5">
                    hubungi saya
                </a>
            </div>
        </div>
    </section>
    <!-- end hero section -->

    <!-- start seection -->
    <section class="flex flex-wrap">
        <div class="w-full self-start px-4 lg:w-1/2">
            <div class="relative mt-10 lg:mt-0 lg:right-0">
                <img src="/ilustrasi/Personal-data-bro.svg" alt="coding ilustrasi" class="bg-transparent lg:w-[600px]">

            </div>
        </div>
        <div class="w-full self-center pl-5px lg:pl-[50px] lg:w-1/2">
            <h1 class="text-base text-primary font-semibold md:text-xl mb-5 mx-3 lg:mx-0">
                Halo, Eziansyah
            </h1>
            <p class="text-sm text-primary opacity-90 mb-5 mx-3 lg:mx-0">
                Saya adalah seorang pelajar, serta Web Developer, UI/UX Designer, dan Quality Assurance,<br>
                memberikan solusi terbaik dan efisien untuk setiap permasalahan Anda. <br>
                Saya selalu berinovasi dan berkembang sesuai dengan kebutuhan klien.
            </p>
            <div class="inline mt-10 mx-6">
                <a href="https://drive.google.com/drive/folders/17kR_hRexgDzph4WcTHaNf0HkIsTQ_SeV?hl=id" target="_blank"
                    rel="noopener noreferrer"
                    class="px-4 py-2 w-[200px] h-[50px] bg-transparent hover:border-green-500 hover:text-green-600 outline-none border-b-2 border-primary duration-300 ease-in-out  mr-5">Download
                    CV</a>
                <router-link :to="{ name: 'about' }">
                    <a href="http://"
                        class="px-4 py-2 w-[200px] h-[50px] bg-transparent hover:border-green-500 hover:text-green-600 outline-none border-b-2 border-primary duration-300 ease-in-out">About
                        me</a>
                </router-link>
            </div>
        </div>
    </section>
    <!-- end section -->

    <!-- start section -->
    <section class="flex items-center justify-center w-full h-screen mb-12 bg-fixed bg-center bg-cover custom mt-10">
        <div class="flex flex-wrap p-1 lg:p-5 text-white bg-primary bg-opacity-50 rounded-xl w-[90%] pb-10">
            <h1 class="text-base text-white font-semibold md:text-xl my-5 mx-6">
                Skills
            </h1>
            
            <div class="w-full mx-10 border-b-2 border-dark py-6 px-4 group cursor-pointer hover:border-green-500 relative" onclick="openModal('modal1')">
                01
                <span class="text-base lg:text-2xl text-black font-bold mx-10 opacity-70">Figma</span>
                <span class="text-base lg:text-2xl text-black font-bold mx-4 opacity-70 float-right group-hover:rotate-45 group-hover:text-green-500 ease-in duration-200">
                    <i class="fa fa-paper-plane" aria-hidden="true"></i>
                </span>
                <span class="absolute bottom-2 right-16 opacity-0 group-hover:opacity-100 transition-opacity duration-300 text-green-300 font-medium text-xs lg:text-sm max-w-[700px] text-right">
                    Saya dapat menggunakan Figma untuk membuat prototipe interaktif serta mendesain UI dan UX untuk web dan aplikasi. 
                    Saya juga mampu menerapkan berbagai elemen desain dengan fitur seperti artboard, komponen, dan auto-layout untuk hasil yang profesional.
                </span>
            </div>
            
            <div class="w-full mx-10 border-b-2 border-dark py-6 px-4 group cursor-pointer hover:border-green-500 relative" onclick="openModal('modal2')">
                02
                <span class="text-base lg:text-2xl text-black font-bold mx-10 opacity-70">HTML</span>
                <span class="text-base lg:text-2xl text-black font-bold mx-4 opacity-70 float-right group-hover:rotate-45 group-hover:text-green-500 ease-in duration-200">
                    <i class="fa fa-paper-plane" aria-hidden="true"></i>
                </span>
                <span class="absolute bottom-2 right-16 opacity-0 group-hover:opacity-100 transition-opacity duration-300 text-green-300 font-medium text-xs lg:text-sm max-w-[750px] text-right">
                    Saya dapat membuat tampilan web dengan HTML, menyusun struktur halaman menggunakan &lt;html&gt;, &lt;head&gt;, dan &lt;body&gt;, menampilkan teks, gambar, tautan, tabel, serta formulir. Selain itu, saya dapat mengatur layout dengan &lt;div&gt; dan &lt;span&gt; untuk desain yang lebih fleksibel dan terstruktur.
                </span>                
            </div>
            <div class="w-full mx-10 border-b-2 border-dark py-6 px-4 group cursor-pointer hover:border-green-500 relative" onclick="openModal('modal3')">
                03
                <span class="text-base lg:text-2xl text-black font-bold mx-10 opacity-70">CSS</span>
                <span class="text-base lg:text-2xl text-black font-bold mx-4 opacity-70 float-right group-hover:rotate-45 group-hover:text-green-500 ease-in duration-200">
                    <i class="fa fa-paper-plane" aria-hidden="true"></i>
                </span>
                <span class="absolute bottom-2 right-16 opacity-0 group-hover:opacity-100 transition-opacity duration-300 text-green-300 font-medium text-xs lg:text-sm max-w-[700px] text-right">
                    Saya dapat mendesain halaman web dengan CSS, mengatur warna, font, dan layout menggunakan `color`, `font-family`, `display`, serta membuat tata letak responsif dengan `flexbox` dan `grid`. Saya juga bisa menambahkan efek transisi, animasi, dan hover untuk interaktivitas.</span>
            </div>
            <div class="w-full mx-10 border-b-2 border-dark py-6 px-4 group cursor-pointer hover:border-green-500 relative" onclick="openModal('modal4')">
                04
                <span class="text-base lg:text-2xl text-black font-bold mx-10 opacity-70">Vue Js</span>
                <span class="text-base lg:text-2xl text-black font-bold mx-4 opacity-70 float-right group-hover:rotate-45 group-hover:text-green-500 ease-in duration-200">
                    <i class="fa fa-paper-plane" aria-hidden="true"></i>
                </span>
                <span class="absolute bottom-2 right-16 opacity-0 group-hover:opacity-100 transition-opacity duration-300 text-green-300 font-medium text-xs lg:text-sm max-w-[800px] text-right">
                    Saya dapat membangun tampilan web interaktif dengan Vue.js, menggunakan komponen untuk struktur UI, mengelola binding data dengan v-model, serta mengatur tampilan dinamis dengan v-if, v-for, dan class binding. Saya juga bisa menerapkan animasi, transition, serta membuat desain responsif dengan Vue.</span>
            </div>
            <div class="w-full mx-10 border-b-2 border-dark py-6 px-4 group cursor-pointer hover:border-green-500 relative" onclick="openModal('modal5')">
                05
                <span class="text-base lg:text-2xl text-black font-bold mx-10 opacity-70">Django</span>
                <span class="text-base lg:text-2xl text-black font-bold mx-4 opacity-70 float-right group-hover:rotate-45 group-hover:text-green-500 ease-in duration-200">
                    <i class="fa fa-paper-plane" aria-hidden="true"></i>
                </span>
                <span class="absolute bottom-2 right-16 opacity-0 group-hover:opacity-100 transition-opacity duration-300 text-green-300 font-medium text-xs lg:text-sm max-w-[750px] text-right">
                    Saya dapat membangun web dengan Django, mulai dari membuat tampilan dengan Django Templates hingga menyambungkan API menggunakan Django REST Framework. Saya bisa mengelola data dengan model, views, dan serializers, serta menampilkan data API di frontend menggunakan fetch atau Axios.</span>
            </div>
            </div>
            </section>
</template>

<script>
function openModal(id) {
    document.getElementById(id).classList.remove('hidden');
}
function closeModal(id) {
    document.getElementById(id).classList.add('hidden');
}
</script>


<style scoped>
.custom {
    background-image: url(/ilustrasi/bg-nature.jpg);
}

.inherit {
    max-width: inherit;
}
</style>