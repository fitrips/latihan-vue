<script setup>
import { Carousel } from 'flowbite-vue'
const pictures = [
  {
    'src': 'https://cf.bstatic.com/xdata/images/hotel/max1024x768/329154960.jpg?k=fbf62ccd745e71f122cdab8e02aeedcb12695050a8cdcfff0a9ac07f0de37f78&o=&hp=1',
    'alt': 'Picture 1',
  },
  {
    'src': 'https://cf.bstatic.com/xdata/images/hotel/max1024x768/304248692.jpg?k=43ac74bf2bf132cc908caa4f8ae8552f6de4eff2c2097bf7394b54979c1b1b7a&o=&hp=1',
    'alt': 'Picture 2',
  },
  {
    'src': 'https://media1.cgtrader.com/variants/2tpYory5fb57zJKWimZWXqCa/64d1262c1acde2eb3beef249c4695a8ad88c958dd79db36f763bf631017addd0/landscape%20backyard%20%282%29.jpg',
    'alt': 'Picture 3',
  },

]
</script>
<template>
  <Carousel :pictures="pictures"></Carousel>
</template>
