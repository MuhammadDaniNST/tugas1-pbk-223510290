<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Universitas</template>

    Kampus
    <a href="https://uir.ac.id/" target="_blank" rel="noopener">Universitas Islam Riau</a>
    merupakan universitas tempat saya menuntut ilmu.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Tempat, Tanggal Lahir</template>

    Lahir di
    <a href="https://id.wikipedia.org/wiki/Kota_Pekanbaru" target="_blank" rel="noopener"
      >Kota Pekanbaru</a
    >. The pada tanggal
    <a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ" target="_blank" rel="noopener"
      >19 Mei 2004</a
    >.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Jurusan</template>

    Mengambil jurusan
    <a href="https://www.youtube.com/watch?v=BbeeuzU5Qc8" target="_blank" rel="noopener"
      >Teknik Informatika</a
    >. Saya memiliki NPM
    <a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ" target="_blank" rel="noopener"
      >223510290</a
    >, dan sekarang duduk di kelas
    <a href="https://www.youtube.com/watch?v=BbeeuzU5Qc8" target="_blank" rel="noopener">4A</a>,
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Hobi</template>

    Hobi saya lampirkan sebagai berikut : <br />
    1.
    <a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ" target="_blank" rel="noopener"
      >Bermain Game</a
    ><br />
    2.
    <a href="https://www.youtube.com/watch?v=BbeeuzU5Qc8" target="_blank" rel="noopener"
      >Menonton Youtube</a
    ><br />
    3.
    <a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ" target="_blank" rel="noopener"
      >Menonton Anime</a
    ><br />
    4.
    <a href="https://www.youtube.com/watch?v=SXdTmUsmyKM" target="_blank" rel="noopener">Ngoding</a>
    (ini bohong)
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Social Media</template>

    Jarang menggunakan sosmed selain untuk melihat meme dan mengupload tugas.<br />
    Instagram = @<a href="https://www.instagram.com/danasty29/" target="_blank" rel="noopener"
      >danasty29</a
    >.
  </WelcomeItem>
</template>
