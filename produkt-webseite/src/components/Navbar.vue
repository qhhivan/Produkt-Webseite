<template>
  <v-app-bar app color="white" height="200">
    <v-app-bar-title>
      <v-img
        src="../assets/a-team-test-logo.jpg"
        max-height="200"
        max-width="200"
        contain
      ></v-img>
    </v-app-bar-title>

    <v-tabs v-model="tabs" align-with-title color="red">
      <v-tab :href="links[0]">
        Über das Projekt
      </v-tab>
      <v-tab :href="links[1]">
        Next Steps
      </v-tab>
      <v-tab :href="links[2]">
        Team
      </v-tab>
      <v-tabs-slider color="red"></v-tabs-slider>
    </v-tabs>
  </v-app-bar>
</template>

<script>
export default {
  data() {
    return {
      tabs: null,
    };
  },

  props: {
    links: {
      type: Array,
    },
  },
};
</script>

<style lang="scss" scoped></style>
