<template>
<body class="bg-white">
  <div class="bg-container bottom-[20px]"></div>
  <div class="background-container bottom-[200px]">
    <div class="flex items-center justify-center py-7">
        <div class="relative flex w-full max-w-[60rem] flex-row rounded-xl bg-white bg-clip-border text-gray-700 shadow-md">
          <div class="relative m-0 w-2/5 shrink-0 overflow-hidden rounded-xl rounded-r-none bg-white bg-clip-border text-gray-700">
            <img
              src="assets/css/img/kepalasekolah.png"
              class="h-full w-full object-cover"/>
          </div>
          <div class="p-6">
            <h6 class="text-xl mb-4 block font-sans font-semibold uppercase leading-relaxed tracking-normal text-pink-500 antialiased">
              Sambutan Kepala Sekolah
            </h6>
            <h4 class="mb-2 block font-sans text-3xl font-semibold leading-snug tracking-normal text-blue-gray-900 antialiased">
              Kurniawan, S.Pd, M.Pd.
            </h4>
            <p class="mb-8 block font-sans text-base font-normal leading-relaxed text-gray-700 antialiased">
              Like so many organizations these days, Autodesk is a company in
              transition. It was until recently a traditional boxed software company
              selling licenses. Yet its own business model disruption is only part of
              the story
            </p>
            <a class="inline-block" href="#">
              <NuxtLink to="/sambutan">
                <button
                class="flex select-none items-center gap-2 rounded-lg py-3 px-6 text-center align-middle font-sans text-xs font-bold uppercase text-pink-500 transition-all hover:bg-pink-500/10 active:bg-pink-500/30 disabled:pointer-events-none disabled:opacity-50 disabled:shadow-none"
                type="button">
                Selengkapnya
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke-width="2"
                  stroke="currentColor"
                  aria-hidden="true"
                  class="h-4 w-4">
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    d="M17.25 8.25L21 12m0 0l-3.75 3.75M21 12H3"></path>
                </svg>
              </button>
              </NuxtLink>
              
            </a>
          </div>
        </div>
      </div>
  </div>


  

  <!-- visi misi -->
  <section class="py-16 bg-gray-100">
    <section class="py-12">
    <div class="container mx-auto px-4 text-center">
        <h2 class="text-3xl font-bold text-gray-800 mb-6">Sejarah SMK Negeri 4 Tasikmalaya</h2>
        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-1 gap-8">

            <!-- Card Sejarah -->
            <div class="bg-white rounded-lg shadow-lg overflow-hidden">
                <img src="https://via.placeholder.com/1200x800" alt="Sejarah SMK Negeri 4" class="w-full h-64 object-cover object-center">
                <div class="p-6">
                    <h3 class="text-xl font-semibold text-gray-800 mb-4">Pendirian dan Perjuangan SMK Negeri 4</h3>
                    <p class="text-gray-600 text-sm">
                        Sejalan dengan Program Pemerintah di bidang pendidikan Menengah Kejuruan pada saat itu, yakni pemerataan akses pendidikan, serta tingginya permintaan dari masyarakat di Kecamatan Purbaratu Kota Tasikmalaya untuk adanya SMK Negeri, maka beberapa tokoh masyarakat dan pejabat pemerintah mengusulkan kepada Pemerintah Kota Tasikmalaya dan Provinsi Jawa Barat agar mendirikan SMK Negeri di wilayah tersebut.
                    </p>
                    <p class="text-gray-600 text-sm mt-4">
                        Setelah perjuangan panjang dan kerjasama berbagai pihak, terutama dari Dinas Pendidikan Kota Tasikmalaya, Alhamdulillah pada tahun pelajaran 2010/2011, SMK Negeri 4 Tasikmalaya resmi berdiri. Pada awalnya, SMK Negeri 4 membuka Kompetensi Keahlian Teknik Komputer dan Jaringan dengan jumlah peserta didik baru sebanyak 44 orang. 
                    </p>
                    <p class="text-gray-600 text-sm mt-4">
                        Pada tahap awal, proses belajar mengajar dilaksanakan di SMP Negeri 17 Kota Tasikmalaya, dengan SMK Negeri 2 Kota Tasikmalaya sebagai sekolah induk. Tenaga pendidik dan kependidikan pada awalnya juga dibantu oleh kedua sekolah tersebut. 
                    </p>
                    <p class="text-gray-600 text-sm mt-4">
                        Pada tahun 2012, SMK Negeri 4 Tasikmalaya memperoleh Surat Izin Pendirian berdasarkan keputusan Kepala Badan Pelayanan Perizinan Terpadu Kota Tasikmalaya No. 420/9/SK-BPPT/2012 pada tanggal 6 Februari 2012, yang mengukuhkan eksistensi sekolah ini.
                    </p>
                    
                    <btn>
                      <NuxtLink to="/profil/sejarah.vue"></NuxtLink>
                      lihat selengkapnya</btn       >
                </div>
            </div>

        </div>
    </div>
</section>


    <!-- Visi -->
    <div class="text-center mb-16">
      <h2 class="text-3xl font-semibold text-primary mb-4">Visi & Misi SMK Negeri 4 Tasikmalaya</h2>
      
  <h2 class="text-3xl font-semibold text-center text-gray-800 mb-6">Visi</h2>
      <p class="text-lg text-gray-700 max-w-3xl mx-auto">
        "TERWUJUDNYA LULUSAN YANG CERDAS, AKTIF, KOMPETITIF, ADAPTIF, DAN PRODUKTIF BERLANDASKAN IMAN DAN TAKWA<br>(CAKAP BERIMTAK)"
      </p>
    </div>
    
    <!-- Misi -->

    <section class=" p-6">
  <h2 class="text-3xl font-semibold text-center text-gray-800 mb-6">Misi</h2>
  <div class="flex flex-wrap justify-center gap-6">
    <!-- Misi 1 -->
    <div class="bg-white p-6 rounded-lg shadow-sm max-w-xs flex items-center">
      <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-blue-500 mr-4" fill="none" viewBox="0 0 24 24" stroke="currentColor">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 14l3 3L22 7"></path>
      </svg>
      <div>
        <h3 class="text-lg font-medium text-gray-700">1</h3>
        <p class="text-gray-500 text-sm">Menyiapkan Sumber Daya Manusia yang cerdas dan kompeten baik hardskill maupun softskill.</p>
      </div>
    </div>

    <!-- Misi 2 -->
    <div class="bg-white p-6 rounded-lg shadow-sm max-w-xs flex items-center">
      <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-green-500 mr-4" fill="none" viewBox="0 0 24 24" stroke="currentColor">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12h6M12 9v6"></path>
      </svg>
      <div>
        <h3 class="text-lg font-medium text-gray-700">2</h3>
        <p class="text-gray-500 text-sm">Meningkatkan dan mengembangkan aktifitas serta kreatifitas seluruh warga sekolah dalam berbagai kegiatan positif.</p>
      </div>
    </div>

    <!-- Misi 3 -->
    <div class="bg-white p-6 rounded-lg shadow-sm max-w-xs flex items-center">
      <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-yellow-500 mr-4" fill="none" viewBox="0 0 24 24" stroke="currentColor">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12h6M12 9v6"></path>
      </svg>
      <div>
        <h3 class="text-lg font-medium text-gray-700">3</h3>
        <p class="text-gray-500 text-sm">Mewujudkan manajemen pengelolaan yang efektif, efesien, transparan, akuntabel dan layanan prima.</p>
      </div>
    </div>

    <!-- Misi 4 -->
    <div class="bg-white p-6 rounded-lg shadow-sm max-w-xs flex items-center">
      <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-red-500 mr-4" fill="none" viewBox="0 0 24 24" stroke="currentColor">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 12l5 5L20 7"></path>
      </svg>
      <div>
        <h3 class="text-lg font-medium text-gray-700">4</h3>
        <p class="text-gray-500 text-sm">Menumbuhkan dan mengembangkan potensi dan kemampuan Sumber Daya Manusia yang berdaya saing tinggi melalui berbagai kegiatan akademik maupun non akademik.</p>
      </div>
    </div>

    <!-- Misi 5 -->
    <div class="bg-white p-6 rounded-lg shadow-sm max-w-xs flex items-center">
      <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-indigo-500 mr-4" fill="none" viewBox="0 0 24 24" stroke="currentColor">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3"></path>
      </svg>
      <div>
        <h3 class="text-lg font-medium text-gray-700">5</h3>
        <p class="text-gray-500 text-sm">Menyelenggarakan berbagai program kegiatan dalam upaya meningkatkan Sumber Daya Manusia yang mampu menyesuaikan dengan perkembangan.</p>
      </div>
    </div>

    <!-- Misi 6 -->
    <div class="bg-white p-6 rounded-lg shadow-sm max-w-xs flex items-center">
      <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-pink-500 mr-4" fill="none" viewBox="0 0 24 24" stroke="currentColor">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 4v16m8-8H4"></path>
      </svg>
      <div>
        <h3 class="text-lg font-medium text-gray-700">6</h3>
        <p class="text-gray-500 text-sm">Mengembangkan sarana prasarana dan lingkungan sekolah yang menyenangkan sebagai wadah menumbuhkembangkan daya kreasi dan inovasi untuk menghasilkan produk teknologi tepat guna.</p>
      </div>
    </div>

    <!-- Misi 7 -->
    <div class="bg-white p-6 rounded-lg shadow-sm max-w-xs flex items-center">
      <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-teal-500 mr-4" fill="none" viewBox="0 0 24 24" stroke="currentColor">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 4v16h16V4H4z"></path>
      </svg>
      <div>
        <h3 class="text-lg font-medium text-gray-700">7</h3>
        <p class="text-gray-500 text-sm">Membangun jiwa wirausaha yang handal melalui pembelajaran Teaching Factory (TEFA) dan Kelas Industri.</p>
      </div>
    </div>

    <!-- Misi 8 -->
    <div class="bg-white p-6 rounded-lg shadow-sm max-w-xs flex items-center">
      <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-gray-500 mr-4" fill="none" viewBox="0 0 24 24" stroke="currentColor">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12h6M12 9v6"></path>
      </svg>
      <div>
        <h3 class="text-lg font-medium text-gray-700">8</h3>
        <p class="text-gray-500 text-sm">Menjalin dan mengembangkan kemitraan dengan Industri dan Dunia Kerja (IDUKA) serta lembaga lainnya yang relevan.</p>
      </div>
    </div>

    <!-- Misi 9 -->
    <div class="bg-white p-6 rounded-lg shadow-sm max-w-xs flex items-center">
      <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-orange-500 mr-4" fill="none" viewBox="0 0 24 24" stroke="currentColor">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 12l5 5L20 7"></path>
      </svg>
      <div>
        <h3 class="text-lg font-medium text-gray-700">9</h3>
        <p class="text-gray-500 text-sm">Menanamkan dan membudayakan sikap dan perilaku yang baik pada aktivitas di sekolah maupun dalam kehidupan sehari-hari.</p>
      </div>
    </div>
  </div>
</section>







</section>



</body>
</template>

<style scoped>
.background-container {
  background-image: url('/assets/css/img/bggrey.jpg');
  background-size: cover;
  background-position: center;
  height: 100vh;
}

.bg-container {
  background-image: url('/assets/css/img/bghome.jpg');
  background-size: cover;
  background-position: center;
  height: 70vh;
}
</style>

