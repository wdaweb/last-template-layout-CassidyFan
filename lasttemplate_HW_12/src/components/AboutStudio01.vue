<template>
      <section id="section2" class="about-background">
        <v-row class="d-flex align-center justify-center text-center">
          <v-col cols="12" md="3">
            <v-img
              src="../assets/section2/black.jpeg"
              alt="About Image"
              class="about-image"
            ></v-img>
          </v-col>
          <v-col cols="12" md="4" class="d-flex flex-column justify-center">
            <div>
              <blockquote><h1 class="about-text">about studio</h1></blockquote>
              <p class="about-p">Quickly incentivize impactful action items before tactical collaboration and idea-sharing. Monotonically engage market-driven intellectual capital through wireless opportunities. Progressively network performance based services for functionalized testing procedures.</p>
            </div>
          </v-col>
          <v-col cols="12" md="1">
            <div class="square"></div>
          </v-col>
        </v-row>
      </section>
      <section id="section3" class="border-bottom">
  <v-img src="@/assets/section3/swimming.jpeg">
    <v-row class="d-flex justify-space-between" style="margin-top: 493px; padding-bottom: 20px;">
      <v-col style="margin-left: 150px;">
        <h3 style="color: white;">BRANDING 36</h3>
        <p style="color: white; max-width: 70%;">We create and execute strategies, aligning with stakeholders to achieve objectives.&nbsp;</p>
      </v-col>
      <v-col>
        <p style="color: white; max-width: 70%; margin-bottom: -72px;">Honed at hundreds of technology companies, our innovative, capital-efficient model is field-tested and, quite simply, works.</p>
      </v-col>
      <v-col class="content" style="margin-left: 100px;">
        <h1 style="font-size: 5rem; color: white; max-width: 100%;">josh lou</h1>
      </v-col>
    </v-row>
  </v-img>
</section>
</template>
<style scoped>
#section2{
  width: 100vw;
  background-color: cadetblue;
  .about-background {
  min-height: 100vh;
}

.about-image {
  max-width: 100%;
  padding-right: 15%;
}

blockquote {
  position: relative;
  padding-right: 217px;
  /* margin-top: 0%; */
}

blockquote::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  width: 10px;
  height: 100%;
  background-color: #FFF;
}

.about-text {
  color: #fff;
  font-size: 100px;
  font-weight: bolder;
  line-height: 6rem;
}

.about-p {
  width: 60%;
  color: #fff;
  font-weight: bolder;
  text-align: left;
  line-height: 2rem;
  padding-top: 5%
}

.square {
  width: 120px;
  height: 120px;
  background: #000;
  margin-top: 400%;
  margin-left: -120%;
}
}
#section3{
  width: 100vw;
}
</style>
