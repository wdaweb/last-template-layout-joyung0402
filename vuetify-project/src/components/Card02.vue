<template>
  <v-row class="mx-auto my-16" style="max-width: 90%;" data-aos="fade-up" data-aos-duration="1000">
    <v-col cols="12" sm="6" md="3">
      <v-card
        :disabled="loading"
        :loading="loading"
        class="mx-auto"
        max-width="100%"
        style="background-color: white; color: black; border-radius: 10px;"
      >
        <template v-slot:loader="{ isActive }">
          <v-progress-linear
            :active="isActive"
            color="deep-purple"
            height="4"
            indeterminate
          ></v-progress-linear>
        </template>

        <v-img
          src="../assets/x01.jpg"
          height="350"
          cover
          style="border-top-left-radius: 10px; border-top-right-radius: 10px;"
        ></v-img>

        <v-card-item>
          <v-card-title>Cafe Badilico</v-card-title>
        </v-card-item>

        <v-card-text>
          <div>Small plates, salads & sandwiches - an intimate setting with 12 indoor seats plus patio seating.</div>
        </v-card-text>

        <v-divider class="mx-4 mb-1"></v-divider>

        <v-card-actions>
          <v-btn
            color="deep-purple-lighten-2"
            text
            block
            style="color: orange!important;"
            border
            @click="reserve"
          >Reserve</v-btn>
        </v-card-actions>
      </v-card>
    </v-col>

    <v-col cols="12" sm="6" md="3">
      <v-card
        :disabled="loading"
        :loading="loading"
        class="mx-auto"
        max-width="100%"
        style="background-color: white; color: black; border-radius: 10px;"
      >
        <template v-slot:loader="{ isActive }">
          <v-progress-linear
            :active="isActive"
            color="deep-purple"
            height="4"
            indeterminate
          ></v-progress-linear>
        </template>

        <v-img
          src="../assets/x02.jpg"
          height="350"
          cover
          style="border-top-left-radius: 10px; border-top-right-radius: 10px;"
        ></v-img>

        <v-card-item>
          <v-card-title>Cafe Badilico</v-card-title>
        </v-card-item>

        <v-card-text>
          <div>Small plates, salads & sandwiches - an intimate setting with 12 indoor seats plus patio seating.</div>
        </v-card-text>

        <v-divider class="mx-4 mb-1"></v-divider>

        <v-card-actions>
          <v-btn
            color="deep-purple-lighten-2"
            text
            block
            style="color: orange!important;"
            border
            @click="reserve"
          >Reserve</v-btn>
        </v-card-actions>
      </v-card>
    </v-col>

    <v-col cols="12" sm="6" md="3">
      <v-card
        :disabled="loading"
        :loading="loading"
        class="mx-auto"
        max-width="100%"
        style="background-color: white; color: black; border-radius: 10px;"
      >
        <template v-slot:loader="{ isActive }">
          <v-progress-linear
            :active="isActive"
            color="deep-purple"
            height="4"
            indeterminate
          ></v-progress-linear>
        </template>

        <v-img
          src="../assets/x03.jpg"
          height="350"
          cover
          style="border-top-left-radius: 10px; border-top-right-radius: 10px;"
        ></v-img>

        <v-card-item>
          <v-card-title>Cafe Badilico</v-card-title>
        </v-card-item>

        <v-card-text>
          <div>Small plates, salads & sandwiches - an intimate setting with 12 indoor seats plus patio seating.</div>
        </v-card-text>

        <v-divider class="mx-4 mb-1"></v-divider>

        <v-card-actions>
          <v-btn
            color="deep-purple-lighten-2"
            text
            block
            style="color: orange!important;"
            border
            @click="reserve"
          >Reserve</v-btn>
        </v-card-actions>
      </v-card>
    </v-col>

    <v-col cols="12" sm="6" md="3">
      <v-card
        :disabled="loading"
        :loading="loading"
        class="mx-auto"
        max-width="100%"
        style="background-color: white; color: black; border-radius: 10px;"
      >
        <template v-slot:loader="{ isActive }">
          <v-progress-linear
            :active="isActive"
            color="deep-purple"
            height="4"
            indeterminate
          ></v-progress-linear>
        </template>

        <v-img
          src="../assets/x04.jpg"
          height="350"
          cover
          style="border-top-left-radius: 10px; border-top-right-radius: 10px;"
        ></v-img>

        <v-card-item>
          <v-card-title>Cafe Badilico</v-card-title>
        </v-card-item>

        <v-card-text>
          <div>Small plates, salads & sandwiches - an intimate setting with 12 indoor seats plus patio seating.</div>
        </v-card-text>

        <v-divider class="mx-4 mb-1"></v-divider>

        <v-card-actions>
          <v-btn
            color="deep-purple-lighten-2"
            text
            block
            style="color: orange!important;"
            border
            @click="reserve"
          >Reserve</v-btn>
        </v-card-actions>
      </v-card>
    </v-col>

    <v-col cols="12" sm="6" md="3">
      <v-card
        :disabled="loading"
        :loading="loading"
        class="mx-auto"
        max-width="100%"
        style="background-color: white; color: black; border-radius: 10px;"
      >
        <template v-slot:loader="{ isActive }">
          <v-progress-linear
            :active="isActive"
            color="deep-purple"
            height="4"
            indeterminate
          ></v-progress-linear>
        </template>

        <v-img
          src="../assets/x05.jpg"
          height="350"
          cover
          style="border-top-left-radius: 10px; border-top-right-radius: 10px;"
        ></v-img>

        <v-card-item>
          <v-card-title>Cafe Badilico</v-card-title>
        </v-card-item>

        <v-card-text>
          <div>Small plates, salads & sandwiches - an intimate setting with 12 indoor seats plus patio seating.</div>
        </v-card-text>

        <v-divider class="mx-4 mb-1"></v-divider>

        <v-card-actions>
          <v-btn
            color="deep-purple-lighten-2"
            text
            block
            style="color: orange!important;"
            border
            @click="reserve"
          >Reserve</v-btn>
        </v-card-actions>
      </v-card>
    </v-col>

    <v-col cols="12" sm="6" md="3">
      <v-card
        :disabled="loading"
        :loading="loading"
        class="mx-auto"
        max-width="100%"
        style="background-color: white; color: black; border-radius: 10px;"
      >
        <template v-slot:loader="{ isActive }">
          <v-progress-linear
            :active="isActive"
            color="deep-purple"
            height="4"
            indeterminate
          ></v-progress-linear>
        </template>

        <v-img
          src="../assets/x06.jpg"
          height="350"
          cover
          style="border-top-left-radius: 10px; border-top-right-radius: 10px;"
        ></v-img>

        <v-card-item>
          <v-card-title>Cafe Badilico</v-card-title>
        </v-card-item>

        <v-card-text>
          <div>Small plates, salads & sandwiches - an intimate setting with 12 indoor seats plus patio seating.</div>
        </v-card-text>

        <v-divider class="mx-4 mb-1"></v-divider>

        <v-card-actions>
          <v-btn
            color="deep-purple-lighten-2"
            text
            block
            style="color: orange!important;"
            border
            @click="reserve"
          >Reserve</v-btn>
        </v-card-actions>
      </v-card>
    </v-col>

    <v-col cols="12" sm="6" md="3">
      <v-card
        :disabled="loading"
        :loading="loading"
        class="mx-auto"
        max-width="100%"
        style="background-color: white; color: black; border-radius: 10px;"
      >
        <template v-slot:loader="{ isActive }">
          <v-progress-linear
            :active="isActive"
            color="deep-purple"
            height="4"
            indeterminate
          ></v-progress-linear>
        </template>

        <v-img
          src="../assets/x07.jpg"
          height="350"
          cover
          style="border-top-left-radius: 10px; border-top-right-radius: 10px;"
        ></v-img>

        <v-card-item>
          <v-card-title>Cafe Badilico</v-card-title>
        </v-card-item>

        <v-card-text>
          <div>Small plates, salads & sandwiches - an intimate setting with 12 indoor seats plus patio seating.</div>
        </v-card-text>

        <v-divider class="mx-4 mb-1"></v-divider>

        <v-card-actions>
          <v-btn
            color="deep-purple-lighten-2"
            text
            block
            style="color: orange!important;"
            border
            @click="reserve"
          >Reserve</v-btn>
        </v-card-actions>
      </v-card>
    </v-col>

    <v-col cols="12" sm="6" md="3">
      <v-card
        :disabled="loading"
        :loading="loading"
        class="mx-auto"
        max-width="100%"
        style="background-color: white; color: black; border-radius: 10px;"
      >
        <template v-slot:loader="{ isActive }">
          <v-progress-linear
            :active="isActive"
            color="deep-purple"
            height="4"
            indeterminate
          ></v-progress-linear>
        </template>

        <v-img
          src="../assets/x08.jpg"
          height="350"
          cover
          style="border-top-left-radius: 10px; border-top-right-radius: 10px;"
        ></v-img>

        <v-card-item>
          <v-card-title>Cafe Badilico</v-card-title>
        </v-card-item>

        <v-card-text>
          <div>Small plates, salads & sandwiches - an intimate setting with 12 indoor seats plus patio seating.</div>
        </v-card-text>

        <v-divider class="mx-4 mb-1"></v-divider>

        <v-card-actions>
          <v-btn
            color="deep-purple-lighten-2"
            text
            block
            style="color: orange!important;"
            border
            @click="reserve"
          >Reserve</v-btn>
        </v-card-actions>
      </v-card>
    </v-col>
  </v-row>
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
      loading: false,
      selection: 1,
    }),

    methods: {
      reserve () {
        this.loading = true

        setTimeout(() => (this.loading = false), 2000)
      },
    },
  }
</script>
