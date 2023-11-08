<template>
  <flickity :options="flickityOptions" class="projects">
    <div class="carousel-cell" v-for="card in cardsInfo" :key="card.id">
      <a :href='card.cardLink'>
        <h4 class="carousel-cell__title">{{card.title}}</h4>
        <p class="carousel-cell__desr">{{card.descr}}</p>
        <div class="carousel-cell__tools">
          <div class="carousel-cell__tools__item--main">{{card.toolsMain}}</div>
          <div class="carousel-cell__tools__item" v-for="tool in card.toolsSecond" :key="tool">{{tool}}</div>
        </div>
        <img :src='card.img' class="carousel-cell__img" :alt='card.title'>
      </a>
    </div>
  </flickity>

  <!-- if you don't want to use the buttons Flickity provides -->
</template>

<script>
import './style.css';

import Flickity from 'vue-flickity';

export default {
  props: {
    cardsInfo: {
      type: Array,
      required: true,
    },
  },
  components: {
    Flickity
  },
  data() {
    return{
      flickityOptions: {
        initialIndex: 0,
        prevNextButtons: false,
        pageDots: false,
        wrapAround: false

        // any options from Flickity can be used
      }
    }
  },
};
</script>

<style scoped>

</style>
