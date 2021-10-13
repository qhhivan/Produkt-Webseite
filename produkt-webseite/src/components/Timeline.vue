<template>
  <v-container>
    <v-timeline>
      <v-timeline-item
        v-for="(status, i) in status"
        :key="i"
        :color="status.color"
        small
      >
        <template v-slot:opposite>
          <span
            :class="`headline font-weight-bold ${status.color}--text`"
            v-text="status.status"
          ></span>
        </template>

        <!-- <div class="py-4" v-for="i in tasks"
        :key="i">
          <h2 :class="`headline font-weight-light mb-4 ${status.color}--text`">
            {{i.headline}}
          </h2>
          <div>
            {{i.text}}
          </div>
        </div> -->

        <div class="py-4">
          <h2 :class="`headline font-weight-light mb-4 ${status.color}--text`">
            Lorem ipsum
          </h2>
          <div>
            Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
            nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam
            erat, sed diam voluptua. At vero eos et accusam et justo duo dolores
            et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est
            Lorem ipsum dolor sit amet.
          </div>
        </div>
      </v-timeline-item>
    </v-timeline>
  </v-container>
</template>

<script>
export default {
  data: () => ({
    status: [
      {
        color: 'green',
        status: 'Done',
      },
      {
        color: 'blue',
        status: 'In Progress',
      },
      {
        color: 'grey',
        status: 'Next Step',
      },
    ],

    tasks: [
      {
        headline: 'Moodboard',
        text:
          'Lorem ipsum dolor sit amet, no nam oblique veritus. Commune scaevola imperdiet nec ut, sed euismod convenire principes at. Est et nobis iisque percipit, an vim zril disputando voluptatibus, vix an salutandi sententiae.',
      },
      {
        headline: 'Produkt Webseite',
        text:
          'Lorem ipsum dolor sit amet, no nam oblique veritus. Commune scaevola imperdiet nec ut, sed euismod convenire principes at. Est et nobis iisque percipit, an vim zril disputando voluptatibus, vix an salutandi sententiae.',
      },
      {
        headline: 'Poster',
        text:
          'Lorem ipsum dolor sit amet, no nam oblique veritus. Commune scaevola imperdiet nec ut, sed euismod convenire principes at. Est et nobis iisque percipit, an vim zril disputando voluptatibus, vix an salutandi sententiae.',
      },
    ],
  }),
};
</script>

<style lang="scss" scoped></style>
