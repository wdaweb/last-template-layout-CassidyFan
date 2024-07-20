<template>
    <section id="section01">
      <swiper
        :modules="modules"
        :slides-per-view="1"
        :space-between="0"
        :loop="true"
        :autoplay="{
          delay: 4000,
          disableOnInteraction: false,
        }"

        @swiper="onSwiper"
        @slideChange="onSlideChange"
        ref="mySwiper"
      >
        <swiper-slide>
          <img src="@/assets/section1/apple.jpeg" class="main_img">
          <div class="swiper_text text-lg-h5">
            <h1 style="font-weight: bolder; font-size: 50px;">web studio</h1>
            <p style="text-decoration: underline;">READ MORE</p>
          </div>

        </swiper-slide>
        <swiper-slide >
          <img src="@/assets/section1/apple.jpeg" class="main_img">
          <div class="swiper_text text-lg-h5">
            <h1 style="font-weight: bolder; font-size: 50px;">web studio</h1>
            <p style="text-decoration: underline;">READ MORE</p>
          </div>
        </swiper-slide>
        <swiper-slide>
          <img src="@/assets/section1/apple.jpeg" class="main_img">
          <div class="swiper_text text-lg-h5">
            <h1 style="font-weight: bolder; font-size: 50px;">web studio</h1>
            <p style="text-decoration: underline;">READ MORE</p>
          </div>
        </swiper-slide>
        <swiper-slide>
          <img src="@/assets/section1/apple.jpeg" class="main_img">
          <div class="swiper_text text-lg-h5">
            <h1 style="font-weight: bolder; font-size: 50px;">web studio</h1>
            <p style="text-decoration: underline;">READ MORE</p>
          </div>
        </swiper-slide>
      </swiper>
    </section>
  </template>

<script>
import { Swiper, SwiperSlide } from 'swiper/vue'
import 'swiper/css'
import 'swiper/css/autoplay'
import { Autoplay } from 'swiper/modules'

export default {
  components: {
    Swiper,
    SwiperSlide
  },
  setup () {
    const onSwiper = (swiper) => {
      console.log(swiper)
    }
    const onSlideChange = () => {
      console.log('slide change')
    }
    const modules = [Autoplay]
    return {
      onSwiper,
      onSlideChange,
      modules
    }
  },
  mounted () {
    this.$nextTick(() => {
      const swiper = this.$refs.mySwiper.swiper
      if (swiper && swiper.params) {
        swiper.params.autoplay = {
          delay: 3000,
          disableOnInteraction: false
        }
        swiper.autoplay.start()
      }
    })
  }
}
</script>

<style scoped>
#section01{
  width: 100vw;
  height: 90vh;
  overflow: hidden;
  .swiper{
    height: 100%;
  }
  .swiper_text{
    text-align: center;
    position: absolute;
    top: 44%;
    left: 49%;
    transform: translate(-50%,-90%);
  }
  .swiper-slide{
    text-align: center;
  }
  .main_img{
    width: 100%;
    height: 100%;
    object-fit: cover;
  }

}
</style>
