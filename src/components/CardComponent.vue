<script setup>
import { TheCard,Rating } from 'flowbite-vue'
</script>
<template>
<br>
<br>
<br>
<p style="font-size: xx-large;"><center><b>VILLA B1</b></center></p>
<br>
<div class="grid grid-cols-3 gap-9 m-8">

  <the-card variant="image" img-src="https://i1.wp.com/www.agoda.com/wp-content/uploads/2019/12/Bali-vacation-homes-Luxury-Modern-Villas-in-Seminyak.jpg?ssl=1" img-alt="Desk">
    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">V. ADENIUM</h5>
    <p class="font-normal text-gray-700 dark:text-gray-400">
        Villa yang berkapasitas 10 orang sampai 20 orang ini tentunya memilki segal spesifikasi yang ditawarkan. Spesifikasi yang ditawarkan villa ini, antara lain kamar tidur tiga buah yang sudah ber-AC, kamar mandi 2 buah, dapur, ruang makan, ruang tamu, hingga tempat parkir . spesifikasi lainya halaman yang dilengkapi dengan gazebo, dan kolam renang pribadi.
    </p>
    <Rating
      :rating="1"
      :scale="1"
      review-text="200+ reviews"
      review-link="#"
    >
      <template #besideText>
        <p class="ml-2 text-sm font-bold text-gray-900 dark:text-white">5.90</p>
      </template>
    </Rating>
  </the-card>

  <the-card variant="image" img-src="https://arafuru.com/wp-content/uploads/2019/09/desain-vila-dan-kolam-renang.jpg" img-alt="Desk" >
    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">V. ANGGREK</h5>
    <p class="font-normal text-gray-700 dark:text-gray-400">
        Villa ini cocok untuk Anda yang ingin berlibur bersama keluarga besar.Peralatan makan dan memasak yang lengkap bisa membuat Anda memasak dengan bahan-bahan yang telah dibawa. Pada malam hari, Anda dapat melakukan BBQ bersama dengan anggota keluarga. Fasilitas lainnya ialah Sofa, Televisis LED,Karaoke, Dispenser, Magicom hingga Kulkas.
    </p>
    <Rating
      :rating="1"
      :scale="1"
      review-text="180 reviews"
      review-link="#"
    >
      <template #besideText>
        <p class="ml-2 text-sm font-bold text-gray-900 dark:text-white">5.20</p>
      </template>
    </Rating>
  </the-card>

  <the-card variant="image" img-src="https://indoproperti88.com/wp-content/uploads/2021/06/WhatsApp-Image-2021-06-24-at-13.29.49.jpeg" img-alt="Desk">
    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">V. MAWAR</h5>
    <p class="font-normal text-gray-700 dark:text-gray-400">
        Semua kamar di Villa Mawar luas dan ber-AC. Fasilitas yang tersedia di dalam kamar, antara lain area tempat duduk, TV layar datar, dan lemari es. Air mineral gratis dan teko listrik juga disediakan jika kamu ingin membuat kopi dan teh di kamar.  Kamar mandi pribadinya dilengkapi dengan shower dan peralatan mandi gratis. Villa berisi dua kamar juga tersedia.
    </p>
    <Rating
      :rating="1"
      :scale="1"
      review-text="179 reviews"
      review-link="#"
    >
      <template #besideText>
        <p class="ml-2 text-sm font-bold text-gray-900 dark:text-white">5.00</p>
      </template>
    </Rating>
  </the-card>
</div>
<br>
<br>

</template>



