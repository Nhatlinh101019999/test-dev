<template>
  <div class="container mx-auto px-4">
    <div ref="swiper" class="swiper">
      <div class="swiper-wrapper">
        <HeaderVue class="swiper-slide" />
        <galleryimg class="swiper-slide" />
      </div>
    </div>
  </div>
</template>

<script>
import Swiper, { Navigation, Pagination } from 'swiper'
import HeaderVue from '../components/Header/HeaderNuxt.vue'
import Galleryimg from '../components/Footer/Galleryimg.vue'

// import styles bundle
import 'swiper/swiper-bundle.min.css'

export default {
  name: 'IndexPage',
  components: { HeaderVue, Galleryimg },
  mounted () {
    const SECOND = 1000 // milliseconds
    // eslint-disable-next-line no-new
    new Swiper(this.$refs.swiper, {
      // configure Swiper to use modules
      modules: [Navigation, Pagination],

      loop: true,
      autoplay: {
        delay: 3 * SECOND,
        disableOnInteraction: false
      },
      speed: 2 * SECOND,
      pagination: {
        el: '.swiper-pagination',
        clickable: true
      },
      navigation: {
        nextEl: '.swiper-button-next',
        prevEl: '.swiper-button-prev'
      },

      // Events
      on: {
        slideChange: (swiper) => {
          this.activeIndex = swiper.realIndex
        }
      }
    })
  }
}
</script>
