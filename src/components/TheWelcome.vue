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
      <TENTANG DIRI SAYAIcon />
    </template>
    <template #heading>TENTANG DIRI SAYA</template>

  
    <a href="https://vuejs.org/" target="_blank" rel="noopener"></a>
    Saya seorang mahasiswa Universitas Islam Riau dari Jurusan Teknik Informatika yang sekarang berada disemester 4. Saya mempunyai hobi membaca,mendengar musik dan bermain game.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <DATA PRIBADIIcon />
    </template>
    <template #heading>DATA PRIBADI</template>
    Nama : Najwa Lutfia Nisya
    <br> Npm : 223510903
    <br> Tempat/tgl.lahir : Pekanbaru/ 14 Maret 2004
    <br> Jenis Kelamin : Perempuan

    <br />

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <PENDIDIKANIcon />
    </template>
    <template #heading>PENDIDIKAN</template>
    SD YPPI TUALANG
    TAHUN 2010-2016
    <br> SMP YPPI TUALANG
    TAHUN 2016-2019
    <br> SMA 1 TUALANG
    TAHUN 2019-2022
    <br> UNIVERSITAS ISLAM Riau
    TAHUN 2022-SEKARANG

  </WelcomeItem>

  
   <WelcomeItem>
    <template #icon>
      <KESUKAANIcon />
    </template>
    <template #heading> KESUKAAN </template>
    Membaca Novel, Komik
   <br> Menonton Film
    <br> Jalan - jalan
    <br> Mendengar Musik

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CONTACTIcon />
    </template>
    <template #heading>CONTACT</template>
    No.hp : 082283218772
    <br> Instagram : najwalutfiaa_
    <br> Email : najwalutfianisya@gmail.com

    
  </WelcomeItem>
</template>
