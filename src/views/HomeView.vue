<template>
  <div class="home">
     <NavbarHeader/>
   <OwlCarousel/>
   <SliderBawah/>
   <InstaSlide/>
   <PartnerLogo/>
   <FooterGa/>
  </div>
</template>

<script>
// @ is an alias to /src
import NavbarHeader from '@/components/NavbarHeader.vue';
import OwlCarousel from '@/components/OwlCarousel.vue';
import SliderBawah from '@/components/SliderBawah.vue';
import InstaSlide from '@/components/InstaSlide.vue';
import PartnerLogo from '@/components/PartnerLogo.vue';
import FooterGa from '@/components/FooterGa.vue';
export default {
  name: 'HomeView',
  components: {
    NavbarHeader,
    OwlCarousel,
    SliderBawah,
    InstaSlide,
    PartnerLogo,
    FooterGa
  }
}
</script>
