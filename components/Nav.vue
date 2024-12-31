<template>
   <div class="navbar relative bg-base-100">
  <div class="flex-none relative left-[500px]">
    <ul class="menu relative menu-horizontal px-1 gap-4">
      <li>
        <details>
          <summary>Profil</summary>
          <ul class="bg-base-100 rounded-t-none p-2">
            <li> <NuxtLink to="/identitas"><a>Identitas Sekolah</a> </NuxtLink></li>
            <li> <NuxtLink to="/sejarah"><a>Sejarah</a> </NuxtLink></li>
            <li> <NuxtLink to="/profil/visimisi"><a>Visi & Misi</a> </NuxtLink></li>
            <li> <NuxtLink to="/kepsek"><a>Kepala Sekolah</a> </NuxtLink></li>
            <li> <NuxtLink to="/stor"><a>Struktur Organisasi</a> </NuxtLink></li>
            <li> <NuxtLink to="/profil/guru"><a>Guru & Staf</a> </NuxtLink></li>
   
          </ul>
        </details>
      </li>
      <li>
        <details>
          <NuxtLink to="/jurusan"></NuxtLink>
          <summary>Konsentrasi Keahlian</summary>
          <ul class="bg-base-100 rounded-t-none p-2">
            <li><a>TJKT</a></li>
            <li><a>PPLG</a></li>
            <li><a>TSM</a></li>
            <li><a>DKV</a></li>
            <li><a>TOI</a></li>
          </ul>
        </details>
      </li>
      <li>
        <details>
          <summary>Ekstrakulikuler</summary>
          <ul class="bg-base-100 rounded-t-none p-2">
            <li><a>Link 1</a></li>
            <li><a>Link 2</a></li>
          </ul>
        </details>
      </li>
      <li>
        <details>
          <summary>Sapras</summary>
          <ul class="bg-base-100 rounded-t-none p-2">
            <li><a>Link 1</a></li>
            <li><a>Link 2</a></li>
          </ul>
        </details>
      </li>
      <li>
        <details>
          <NuxtLink to="/galeri"></NuxtLink>
          <summary>Galeri</summary>
          <ul class="bg-base-100 rounded-t-none p-2">
            <li> <NuxtLink to="/glry/hal1"><a>Hari Kemerdekaan</a> </NuxtLink></li>
          </ul>
        </details>
      </li>
      <li>
        <details>
          <summary><NuxtLink to="/berita">Berita</NuxtLink></summary>
        </details>
      </li>
    </ul>
  </div>
</div>
</template>