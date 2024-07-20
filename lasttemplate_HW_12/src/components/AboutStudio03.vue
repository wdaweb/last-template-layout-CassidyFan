<template>
  <section id="section05">
    <v-container>
      <v-row style="max-width: 63%; margin: auto;">
        <v-col class="greenbox" style="max-width: 20%; background-color: turquoise;" data-aos="fade-up">
          <div style="margin: auto; padding: 1.2rem;">
            <h4 style="font-size: 20px; font-weight: bolder;">Create Better Lives</h4>
            <br>
            <p style="font-size: 15px;">We look at architecture from the perspective of the lives it supports and impacts upon, designing homogenous solutions that always consider the needs of the individual and those of the wider community.</p>
          </div>
        </v-col>
        <v-col class="d-flex justify-center" data-aos="fade-up">
          <v-img
            src="../assets/section7/zebra.jpg"
            alt="Zebra Image"
            class="zebra-image"
            style="width: 20%; max-width: 200px;"
          ></v-img>
        </v-col>
        <v-col class="d-flex justify-center" data-aos="fade-up">
          <v-img
            src="../assets/section7/istock03.jpg"
            alt="Image"
            class="image"
            style="width: 100%; max-width: 300px;"
          ></v-img>
        </v-col>
      </v-row>
    </v-container>
  </section>
  <section id="section06">
    <v-container>
      <v-row style="max-width: 63%; margin: auto;">
        <v-col class="d-flex justify-center" data-aos="fade-up">
          <v-img
            src="../assets/section7/istock06.jpg"
            alt="Image"
            class="image"
            style="width: 100%; max-width: 300px;"
          ></v-img>
        </v-col>
        <v-col cols="2" style="height: 50vh; background-color: black; margin: auto;" data-aos="fade-up">
          <v-img
            src="../assets/section7/fingerprint.png"
            alt="Image"
            class="image"
            style="width: 50%; margin: auto;"
          ></v-img>
          <h1 style="color: white; text-align: center;">Arch</h1>
        </v-col>
        <v-col class="greenbox" style="max-width: 20%; background-color: white;" data-aos="fade-up">
          <div style="margin: auto; padding: 1.2rem;">
            <h4 style="font-size: 20px; font-weight: bolder;">Contact Us</h4>
            <br>
            <p style="font-size: 15px;">We look at architecture from the perspective of the lives it supports and impacts upon, designing homogenous solutions that always consider the needs of the individual and those of the wider community.</p>
          </div>
        </v-col>
      </v-row>
    </v-container>
  </section>
</template>

<script>
import AOS from 'aos'
import 'aos/dist/aos.css'

export default {
  name: 'App',
  mounted () {
    AOS.init()
  }
}
</script>

<style scoped>
.image {
  max-width: 300px;
}
#section10 {
  text-align: center;
  overflow-x: scroll;
}
.brand-background {
  background: url('../assets/section10/swimming.jpeg') no-repeat center center;
  background-size: cover;
  position: relative;
  height: 100vh;
}

.content-container {
  position: absolute;
  bottom: 0;
  width: 100%;
}
</style>
