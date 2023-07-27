<script setup>
import { TheCard,Rating } from 'flowbite-vue'
</script>
<template>
<br>
<br>
<br>
<p style="font-size: xx-large;"><center><b>VILLA B3 </b></center></p>
<br>
<div class="grid grid-cols-3 gap-9 m-8">
  <the-card variant="image" img-src="https://www.sewa-villa.com/images1/1029_6.jpg" img-alt="Desk">
    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">V. MIMOSA</h5>
    <p class="font-normal text-gray-700 dark:text-gray-400">
        Villa B3 ini memiliki bentuk bangunan yang sama namun fasilitas berbeda. Cukup sederhana namun memiliki pemandangan yang cukup indah. Kekurangan tanpa wifi dan ruang karaoke    </p>
    <Rating
      :rating="1"
      :scale="1"
      review-text="90 reviews"
      review-link="#"
    >
      <template #besideText>
        <p class="ml-2 text-sm font-bold text-gray-900 dark:text-white">3.90</p>
      </template>
    </Rating>
  </the-card>

  
  <the-card variant="image" img-src="https://www.sewa-villa.com/images1/1029_6.jpg" img-alt="Desk" >
    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">V. ALAMANDA</h5>
    <p class="font-normal text-gray-700 dark:text-gray-400">
        Villa B3 ini memiliki bentuk bangunan yang sama namun fasilitas berbeda.  Cukup sederhana namun memiliki pemandangan yang cukup indah. Kekurangan tanpa karaoke dan tanpa kolam renang.
    </p>
    <Rating
      :rating="1"
      :scale="1"
      review-text="50 reviews"
      review-link="#"
    >
      <template #besideText>
        <p class="ml-2 text-sm font-bold text-gray-900 dark:text-white">4.00</p>
      </template>
    </Rating>
  </the-card>

  <the-card variant="image" img-src="https://www.sewa-villa.com/images1/1029_6.jpg" img-alt="Desk">
    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">V. JASMINE</h5>
    <p class="font-normal text-gray-700 dark:text-gray-400">
        Villa B3 ini memiliki bentuk bangunan yang sama namun fasilitas berbeda. Cukup sederhana namun memiliki pemandangan yang cukup indah. Tidak terdapat kolam renang.
    </p>
    <Rating
      :rating="1"
      :scale="1"
      review-text="50 reviews"
      review-link="#"
    >
      <template #besideText>
        <p class="ml-2 text-sm font-bold text-gray-900 dark:text-white">4.09</p>
      </template>
    </Rating>
  </the-card>
</div>
</template>



