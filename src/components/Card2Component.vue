<script setup>
import { TheCard,Rating } from 'flowbite-vue'
</script>
<template>
    <br>
<br>
<br>
<br>
<p style="font-size: xx-large;"><center><b>VILLA B2</b></center></p>
<br>
<br>
<br>
<div class="grid grid-cols-3 gap-9 m-8">

  <the-card variant="image" img-src="https://ciloto.com/wp-content/uploads/2019/03/IMG-20181213-WA0167-1024x768.jpg" img-alt="Desk">
    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">V. LOTUS</h5>
    <p class="font-normal text-gray-700 dark:text-gray-400">
        Villa lotus terdiri dari bangunan 2 lantai dengan terbagi dari 5 buah kamar tidur, 2 buah kamar mandi, ruang keluarga, balkon, teras, halaman dan car port.
        Fasilitas Karaoke, BBQ, Wifi . tidak dilengkapi kolam renang.
    </p>
    <Rating
      :rating="1"
      :scale="1"
      review-text="110 reviews"
      review-link="#"
    >
      <template #besideText>
        <p class="ml-2 text-sm font-bold text-gray-900 dark:text-white">4.90</p>
      </template>
    </Rating>
  </the-card>

  <the-card variant="image" img-src="https://ciloto.com/wp-content/uploads/2019/04/IMG-20190408-WA0092-1024x768.jpg" img-alt="Desk" >
    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">V. GERANIUM</h5>
    <p class="font-normal text-gray-700 dark:text-gray-400">
        villa geranium 4 kamar tanpa kolam renang . Villa ayu memiliki bangunan 2 lantai dengan 4 buah kamar tidur, 3 buah kamar mandi, ruang keluarga, teras, dapur, balkon dan tempat parkir kendaraan. Harga yang terjangkau dan view yang nyaman.
    </p>
    <Rating
      :rating="1"
      :scale="1"
      review-text="140 reviews"
      review-link="#"
    >
      <template #besideText>
        <p class="ml-2 text-sm font-bold text-gray-900 dark:text-white">4.79</p>
      </template>
    </Rating>
  </the-card>


  <the-card variant="image" img-src="https://pix10.agoda.net/hotelImages/agoda-homes/12536046/5df55a71162b9539cc1c7c8730685413.jpg?ca=10&ce=1" img-alt="Desk">
    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">V. LILY</h5>
    <p class="font-normal text-gray-700 dark:text-gray-400">
       Villa ini terdiri dari bangunan 2 lantai dengan memiliki 6 buah kamar tidur, 3 buah kamar mandi, ruang keluarga, dapur, teras, halaman rumput , gazebo dan tempat parkir yang bisa untuk menyimpan mobil pribadi ataupun bus. Villa ini nyaman untuk digunakan liburan.
    </p>
    <Rating
      :rating="1"
      :scale="1"
      review-text="155 reviews"
      review-link="#"
    >
      <template #besideText>
        <p class="ml-2 text-sm font-bold text-gray-900 dark:text-white">4.60</p>
      </template>
    </Rating>
  </the-card>
  <div class="basis-1/4" mx-5></div>
  <br>
</div>
<br>
<br>
<br>
</template>



