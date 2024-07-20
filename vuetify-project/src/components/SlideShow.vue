<template>
  <swiper
    :cssMode="true"
    :navigation="true"
    :pagination="true"
    :mousewheel="true"
    :keyboard="true"
    :modules="modules"
    class="mySwiper"
  >
    <swiper-slide><img src="../assets/ss02.jpg"></swiper-slide>
    <swiper-slide><img src="../assets/ss01.jpg"></swiper-slide>
  </swiper>
</template>
<script>
  // Import Swiper Vue.js components
  import { Swiper, SwiperSlide } from 'swiper/vue';

  // Import Swiper styles
  import 'swiper/css';

  import 'swiper/css/navigation';
  import 'swiper/css/pagination';

  import '../styles/swiperstyle.css';

  // import required modules
  import { Navigation, Pagination, Mousewheel, Keyboard } from 'swiper/modules';

  export default {
    components: {
      Swiper,
      SwiperSlide,
    },
    setup() {
      return {
        modules: [Navigation, Pagination, Mousewheel, Keyboard],
      };
    },
  };
</script>

<style>
img{
  width: 100%;
  height: 800px;
  object-fit: cover;
}
@media (min-width: 1280px) {
  .mySwiper{
    margin-bottom: 100px;
  }
}

@media (max-width: 600px) {
  .mySwiper{
    margin-bottom: 50px;
  }
}
</style>
