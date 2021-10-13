<template>
  <v-app-bar app color="primary" height="200">
    <v-app-bar-title>
      <v-img
        src="../assets/a-team-test-logo.jpg"
        max-height="200"
        max-width="200"
        contain
      ></v-img>
    </v-app-bar-title>

    <v-breadcrumbs :items="items" divider="/"></v-breadcrumbs>
  </v-app-bar>
</template>

<script>
export default {
  data() {
    return {
      items: [
        {
          text: 'Home',
          disabled: false,
          //   href: '',
        },
        {
          text: 'Über unser Team',
          disabled: false,
          //   href: '',
        },
        {
          text: 'Über das Projekt',
          disabled: false,
          //   href: '',
        },
        {
          text: 'Next Steps',
          disabled: false,
          //   href: '',
        },
      ],
    };
  },
};
</script>

<style lang="scss" scoped></style>