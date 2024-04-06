<script setup lang="ts">
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
    <template #heading>Tentang Saya</template>
    Perkenalkan saya Jeni Agryrosa, saya biasa dipanggil Jeni atau Jeje
    Saya berasa dari Rengat yaitu sebuah Kecamatan sekaligus Ibukota dari Indragiri Hulu,Riau.
    Saya merupakan lulusan dari  <a href="https://smanegeri1rengat.sch.id/index.php" target="_blank" rel="noopener">SMA Negeri 1 Rengat</a>,
    Dan saat ini saya sedang Berkuliah di <a href="https://uir.ac.id/" target="_blank" rel="noopener">Universitas Islam Riau</a> prodi Teknik Informatika (S1)
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Pengalaman</template>
    Saa memiliki beberapa pengalaman yang mungkin dapat menunjukan diri saya :
    <ul>
      <li>Paskibraka</li>
      <li>Osis</li>
      <li>Unit Kesehatan Sekolah</li>
      <li>Palang Merah Indonesia</li>
      <li>Pelatihan Komputer</li>
      <li>Seminar Networking</li>
    </ul>

  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Hobi saya</template>
Untuk mengisi waktu luang saya,saya melakukan kegiatan bermanfaat sebagai hobi saya, yaitu:    <ul>
      <li>Basket</li>
      <li>Jogging</li>
      <li>Nonton</li>
    </ul>
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Skill</template>
Saya memiliki kemampun di bidang IT berupa :    <ul>
      <li>Javascript</li>
      <li>MySql</li>
      <li>Java</li>
      <li>C++</li>
      <li>PHP</li>
    </ul>
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Contact</template>
untuk menghubungi saya kalian dapat mengontak di bawah ini
   sosmed Instagram :<a href="https://www.instagram.com/jenyagryrosa" target="_blank">jenyagryrosa </a
    ><br />
    Email : jeny79845@gmail.com<br />
    No HP : +62 852-6552-0***
  </WelcomeItem>
</template>