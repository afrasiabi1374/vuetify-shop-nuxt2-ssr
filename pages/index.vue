<template>
  <div>
    <carousel :images="images"/>
  </div>
</template>

<script>
import Carousel from '../components/Carousel.vue'
export default {
  name: 'INDEX',
  components: {
    Carousel,
  },
  data () {
    return {
      images: [
        require('~/assets/images/carousel/1.jpg'),
        require('~/assets/images/carousel/2.png'),
        require('~/assets/images/carousel/3.png'),
      ]
    }
  }
}
</script>
    Carousel

<style>

</style>