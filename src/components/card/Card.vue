<template>
  <div class="carousel-container">
    <VueSlickCarousel v-bind="settings">
      <div v-for="(item, index) in items" :key="index" class="carousel-item">
        <img :src="item.image" alt="carousel image" class="carousel-image" />
        <div class="text-container">
          <h3 class="carousel-head">{{ item.head }}</h3>
          <p class="carousel-subtext">{{ item.subtext }}</p>
        </div>
      </div>
    </VueSlickCarousel>
  </div>
</template>

<script>
import VueSlickCarousel from 'vue-slick-carousel';
import 'vue-slick-carousel/dist/vue-slick-carousel.css';

export default {
  components: {
    VueSlickCarousel,
  },
  data() {
    return {
      settings: {
        dots: true,
        infinite: true,
        speed: 500,
        slidesToShow: 1,
        slidesToScroll: 1,
        arrows: true,
      },
      items: [
        {
          image: 'image1.jpg',
          head: 'Title 1',
          subtext: 'Subtext 1',
        },
        {
          image: 'image2.jpg',
          head: 'Title 2',
          subtext: 'Subtext 2',
        },
        {
          image: 'image3.jpg',
          head: 'Title 3',
          subtext: 'Subtext 3',
        },
        {
          image: 'image4.jpg',
          head: 'Title 4',
          subtext: 'Subtext 4',
        },
        {
          image: 'image5.jpg',
          head: 'Title 5',
          subtext: 'Subtext 5',
        },
      ],
    };
  },
};
</script>

<style scoped>
.carousel-container {
  width: 80%;
  margin: 0 auto;
}

.carousel-item {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 1rem;
}

.carousel-image {
  width: 100%;
  height: auto;
  object-fit: cover;
}

.text-container {
  margin-top: 1rem;
  text-align: center;
}

.carousel-head {
  font-size: 1.2rem;
  font-weight: bold;
}

.carousel-subtext {
  font-size: 1rem;
  color: #666;
}
</style>
