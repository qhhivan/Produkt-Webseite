<template>
  <v-container>
    <!-- Nicht Container-Fluid genommen damit bissi abstand auf den Seiten ist -->

    <v-row class="my-3">
      <!-- Eine row hat 12 col -->
      <v-col cols="7">
        <h1>Über unser Team</h1>

        <p class="my-auto">
          Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
          nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat,
          sed diam voluptua. At vero eos et accusam et justo duo dolores et ea
          rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem
          ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur
          sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et
          dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam
          et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea
          takimata sanctus est Lorem ipsum dolor sit amet.
        </p>
      </v-col>

      <v-col>
        <v-img
          src="../assets/team-pic-test.jpg"
          max-height="400"
          max-width="400"
          contain
        ></v-img>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped></style>
