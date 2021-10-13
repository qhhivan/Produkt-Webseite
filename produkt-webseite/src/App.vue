<template>
  <v-app>
    <!-- Menu -->
    <Navbar />

    <!-- Main -->
    <v-main>
      <AboutUs />
    </v-main>
  </v-app>
</template>

<script>
// Import Components
import Navbar from '@/components/Navbar.vue';
import AboutUs from '@/components/AboutUs.vue';

export default {
  name: 'App',

  data: () => ({
    //
  }),

  components: {
    Navbar,
    AboutUs,
  },
};
</script>
