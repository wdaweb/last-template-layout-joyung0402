<template>
  <section data-aos="fade-in" data-aos-duration="2000">
  </section>
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
</script>

<style scoped>
section{
height: 50vh;
background: url("../assets/ft.png");
background-size:contain;
background-repeat: no-repeat;
background-position: bottom center;
}

@media (max-width: 1400px) {
  section{
    height: 40vh;
  }
}

@media (max-width: 600px) {
  section{
    height: 20vh;
  }
}
</style>
