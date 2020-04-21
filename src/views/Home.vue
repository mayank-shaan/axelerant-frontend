<template>
  <div>
    <div class="wrapper">

      <Header />

      <Banner />

      <WorldMap />

      <Testimonials />

      <ContactUs />

      <FooterComponent />

    </div>
  </div>
</template>

<script>
import Header from '@/components/Header.vue';
import Banner from '@/components/Banner.vue';
import WorldMap from '@/components/WorldMap.vue';
import Testimonials from '@/components/Testimonials.vue';
import ContactUs from '@/components/ContactUs.vue';
import FooterComponent from '@/components/FooterComponent.vue';

export default {
  name: 'Home',
  components: {
    Header,
    Banner,
    WorldMap,
    Testimonials,
    ContactUs,
    FooterComponent,
  },
};
</script>
