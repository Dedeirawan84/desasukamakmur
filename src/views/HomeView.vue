<script setup>
import Header from '../components/Header.vue'
import Banner from '../components/Banner.vue'
import Sidebar from '../components/Sidebar.vue'
</script>

<template>
  <Header/>
  <Banner/>
  <main class="flex">
    <Sidebar/>
    <div class="flex-1 p-10">

      <p class="text-3xl font-semibold">Sejarah Singkat Desa</p>
      <p>Desa Sukamakmur terbentuk sejak tahun 1946 tepatnya satu tahun sejak Negara Kesatuan Republik Indonesia menyatakan kemerdekaannya dan saat itu Desa Sukamakmur diberi nama Desa Cihanjawar namun setelah di adakan rembug (Musywarah) dijaman kemerdekaan tepatnya Tahun 1947 maka Desa Cihanjawar sendiri berganti nama menjadi Desa Sukamakmur hingga kini, dari hasil itulah maka terbentuklah sebuah nama Desa yang baku yaitu Desa Sukamakmur.</p>
      <p class="text-3xl font-semibold">Visi & Misi Desa</p>
      <p>Visi:</p>
      <p>“Mewujudkan Desa Sukamakmur Yang Maju, Sejahtera, Agamis, Aman dan Bermartabat”</p>
      <p>Misi:</p>
      <p>
        1. Meningkatkan kualitas pelayanan masyarakat dan penyelenggaraan pemerintahan desa;
      </p>
      <p>
        2. Meningkatkan kualtas perencanaan dan pelaksanaan pembangunan desa;
      </p>
      <p>
        3. Meningkatkan profesionalisme aparatur pemerintah desa;
      </p>
      <p>
        4. Meningkatkan pemahaman, ketaatan dan kepatuhan masyarakat terhadap ketentuan peraturan perundang-undangan yang berlaku;
      </p>
      <p>
        5. Meningkatkan dan mengembangkan partisipasi masyarakat dalam pembangunan desa.
      </p>

      <p class="text-3xl font-semibold my-4">Struktur Desa</p>
      <img src="@/assets/struktur-desa.png" alt=""/>
    </div>
  </main>
</template>

<style>
  body{
    background: #f1f1f1;
  }
</style>
