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
      <v-tab href="#home" >
        Home
      </v-tab>
      <v-tab href="#ueber-team">
        Über unser Team
      </v-tab>
      <v-tab href="#ueber-projekt">
        Über das Projekt
      </v-tab>
      <v-tab href="#next-steps">
        Next Steps
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
};
</script>

<style lang="scss" scoped></style>
