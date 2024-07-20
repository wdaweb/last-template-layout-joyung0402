<template>
  <v-card class="my-16 mx-auto mycards" max-width="90%" style="background: none;box-shadow: none;">
    <v-row dense>
      <v-col :cols="12" md="5">
        <v-card class="responsive-card" data-aos="fade-up" data-aos-duration="4000">
          <v-img
            src="../assets/c01.jpg"
            class="align-end responsive-img"
            gradient="to bottom, rgba(0,0,0,.1), rgba(0,0,0,.5)"
            height="825px"
            cover
          >
            <v-card-title class="text-white">Pre-fab homes</v-card-title>
          </v-img>
        </v-card>
      </v-col>
      <v-col :cols="12" md="7">
        <v-row dense>
          <v-col :cols="12" md="6">
            <v-card class="mb-2 ml-4 responsive-card" data-aos="fade-down" data-aos-duration="3000">
              <v-img
                src="../assets/c02.jpg"
                class="align-end responsive-img"
                gradient="to bottom, rgba(0,0,0,.1), rgba(0,0,0,.5)"
                height="400px"
                cover
              >
                <v-card-title class="text-white">Favorite road trips</v-card-title>
              </v-img>
            </v-card>
          </v-col>
          <v-col :cols="12" md="6">
            <v-card class="mb-2 ml-4 responsive-card" data-aos="fade-down" data-aos-duration="3000">
              <v-img
                src="../assets/c04.jpg"
                class="align-end responsive-img"
                gradient="to bottom, rgba(0,0,0,.1), rgba(0,0,0,.5)"
                height="400px"
                cover
              >
                <v-card-title class="text-white">Best airlines</v-card-title>
              </v-img>
            </v-card>
          </v-col>
          <v-col :cols="12" md="12">
            <v-card class="mt-2 ml-4 responsive-card" data-aos="fade-up" data-aos-duration="5000">
              <v-img
                src="../assets/c03.jpg"
                class="align-end responsive-img"
                gradient="to bottom, rgba(0,0,0,.1), rgba(0,0,0,.5)"
                height="400px"
                cover
              >
                <v-card-title class="text-white">Beautiful scenery</v-card-title>
              </v-img>
            </v-card>
          </v-col>
        </v-row>
      </v-col>
    </v-row>
  </v-card>
</template>

<script>
import AOS from 'aos'
import 'aos/dist/aos.css'
import { gsap } from 'gsap'
import { ScrollTrigger } from 'gsap/ScrollTrigger'
gsap.registerPlugin(ScrollTrigger)
AOS.init({
  once: true
})
export default {
  data: () => ({
    cards: [
      { title: 'Pre-fab homes', src: '../assets/c01.jpg' },
      { title: 'Favorite road trips', src: '../assets/c02.jpg' },
      { title: 'Best airlines', src: '../assets/c04.jpg' },
      { title: 'Beautiful scenery', src: '../assets/c03.jpg' },
    ],
  }),
}
</script>

<style scoped>
/* 在手機設備上設置圖片高度並設置上下間距 */
@media (max-width: 600px) {
  .responsive-img {
    height: 200px !important; /* 使用 !important 以確保在手機上覆蓋內聯樣式 */
  }
  .responsive-card {
    margin-left: 0 !important; /* 移除左邊距 */
    margin-top: 10px !important; /* 設置上邊距 */
    margin-bottom: 10px !important; /* 設置下邊距 */
  }
}

@media (min-width: 1280px) {
  .mycards{
    margin-bottom: 200px!important;
  }
}

@media (max-width: 600px) {
  .mycards{
    margin-bottom: 50px!important;
  }
}
</style>
