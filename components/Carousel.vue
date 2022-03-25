<template>
    <!-- <v-row justify="space-around">
      <v-icon @click="model--">
        mdi-minus
      </v-icon>
      {{ model }}
      <v-icon @click="model++">
        mdi-plus
      </v-icon>
    </v-row> -->
    <v-carousel   v-model="model"  height="850">
      <v-carousel-item 
        
        v-for="(image, i) in images"
        :key="i"
      >
      <img :src="image" width="100%" />
      </v-carousel-item>
    </v-carousel>
</template>
<script>
export default {
  name: 'CAROUSEL',
  props: ['images'],
  data () {
      return {

      }
  }
}
</script>
<style scoped>
</style>
