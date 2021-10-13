<template>
  <v-app>
    <!-- Menu -->
    <Navbar />

    <!-- Main -->
    <v-main>
      <AboutProject />
      <Timeline />
      <AboutUs />
    </v-main>

    <Footer />
  </v-app>
</template>

<script>
// Import Components
import Navbar from '@/components/Navbar.vue';
import AboutUs from '@/components/AboutUs.vue';
import AboutProject from '@/components/AboutProject.vue';
import Timeline from '@/components/Timeline.vue';
import Footer from '@/components/Footer.vue';

export default {
  name: 'App',

  data: () => ({
    //
  }),

  components: {
    Navbar,
    AboutUs,
    AboutProject,
    Timeline,
    Footer,
  },
};
</script>
