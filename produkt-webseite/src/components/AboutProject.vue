<template>
  <v-container>
    <!-- VLT Background leicht ändern -->

    <h1 text-decoration="underline">ÜBER UNSER PROJEKT</h1>

    <!-- Row 1 -->
    <v-row class="my-3">
      <v-col cols="3">
        <v-img
          src="../assets/team-builder-test.jpg"
          max-height="200"
          max-width="200"
          contain
        ></v-img>
      </v-col>

      <v-col cols="9">
        <h2>Worum geht es in unserem Projekt</h2>

        <p class="my-auto">
          Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
          nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat,
          sed diam voluptua. At vero eos et accusam et justo duo dolores et ea
          rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem
          ipsum dolor sit amet.
        </p>
      </v-col>
    </v-row>

    <!-- Row 2 Wie kamen wir auf Unsere Projekt idee -->
    <v-row class="my-3">
      <v-col cols="7">
        <h2>Wie kamen wir auf unsere Projektidee</h2>

        <p class="my-auto">
          Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
          nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat,
          sed diam voluptua. At vero eos et accusam et justo duo dolores et ea
          rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem
          ipsum dolor sit amet.
        </p>
      </v-col>

      <v-col>
        <v-img
          src="../assets/idee.jpg"
          max-height="200"
          max-width="150"
          contain
        ></v-img>
      </v-col>
    </v-row>

    <!-- Row 3 -->
    <v-row class="my-3">
      <v-col cols="3">
        <v-img
          src="../assets/ziel.jpg"
          max-height="200"
          max-width="200"
          contain
        ></v-img>
      </v-col>

      <v-col cols="9">
        <h2>Was ist das Ziel unseres Projekts</h2>

        <p class="my-auto">
          Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
          nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat,
          sed diam voluptua. At vero eos et accusam et justo duo dolores et ea
          rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem
          ipsum dolor sit amet.
        </p>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped></style>
