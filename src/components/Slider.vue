<template>
  <div class="card-b">
    <div class="slider-title mb-5">
      <h2 class="d-flex mb-3">
        <h2 class="underline me-2">Что там</h2>
        <h2 class="color-pink">внутри</h2>
      </h2>
    </div>
    <swiper
      :modules="modules"
      :slides-per-view="slidesPerView"
      :space-between="50"
      :scrollbar="{ draggable: true }"
      @swiper="onSwiper"
      @slideChange="onSlideChange"
      :breakpoints="breakpoints"
    >
      <swiper-slide class="d-flex justify-content-center aling-items-center">
        <img class="swiper-item" src="../assets/images/rooms1.png" alt="" @click="showModal = true"/>
        <div v-if="showModal" class="modal" @click="showModal = false">
          <img
            src="../assets/images/rooms1.png"
            alt="Full Size"
            class="full-size-image"
            @click.stop
          />
        </div>
      </swiper-slide>
      <swiper-slide class="d-flex justify-content-center aling-items-center">
        <img class="swiper-item" src="../assets/images/image1.jpg" alt="">
      </swiper-slide>
      <swiper-slide class="d-flex justify-content-center aling-items-center">
        <img class="swiper-item" src="../assets/images/image2.jpg" alt="">
      </swiper-slide>
      <swiper-slide class="d-flex justify-content-center aling-items-center">
        <img class="swiper-item" src="../assets/images/image3.jpg" alt="">
      </swiper-slide>
      <swiper-slide class="d-flex justify-content-center aling-items-center">
        <img class="swiper-item" src="../assets/images/image4.jpg" alt="">
      </swiper-slide>
      <swiper-slide class="d-flex justify-content-center aling-items-center">
        <img class="swiper-item" src="../assets/images/image5.jpg" alt="">
      </swiper-slide>
    </swiper>
  </div>
</template>

<script>
  // import Swiper core and required modules
  import { Navigation, Pagination, Scrollbar, A11y } from 'swiper/modules';

  // Import Swiper Vue.js components
  import { Swiper, SwiperSlide } from 'swiper/vue';

  // Import Swiper styles
  import 'swiper/css';
  import 'swiper/css/navigation';
  import 'swiper/css/pagination';
  import 'swiper/css/scrollbar';

  export default {
    components: {
      Swiper,
      SwiperSlide,
    },
    data(){
      return{
        showModal: false,
      }
    },
    setup() {
      const onSwiper = (swiper) => {
        console.log(swiper);
      };
      const onSlideChange = () => {
        console.log('slide change');
      };

      const breakpoints = {
        // when window width is >= 640px
        640: {
          slidesPerView: 1,
        },
        // when window width is >= 768px
        1200: {
          slidesPerView: 2,
        },
        // when window width is >= 1024px
        1300: {
          slidesPerView: 3,
        },
        // you can add more breakpoints if needed
      };

      return {
        onSwiper,
        onSlideChange,
        modules: [Navigation, Pagination, Scrollbar, A11y],
        breakpoints,
      };
    },
  };
</script>
