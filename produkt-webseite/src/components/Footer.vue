<template>
  <v-footer color="red" padless>
    <v-row justify="center" no-gutters>
      <v-btn
        v-for="link in links"
        :key="link"
        color="white"
        text
        rounded
        class="my-2"
      >
        {{ link }}
      </v-btn>
      <v-col class="red accent-4 py-4 text-center white--text" cols="12">
        2021 — <strong>Diplomarbeit A-Team</strong>
      </v-col>
    </v-row>
  </v-footer>
</template>

<script>
export default {
  data: () => ({
    links: ['Über das Projekt', 'Next Steps', 'Team'],
  }),
};
</script>
