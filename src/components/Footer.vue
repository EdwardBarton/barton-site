<template>
  <v-footer app height="auto" dark>
    <v-layout justify-center row wrap>
      <v-btn
        v-for="(icon, index) in icons"
        :key="index"
        class="mx-3"
        icon
        target="_blank"
        :href="icon.link"
      >
        <v-icon size="24px">{{ icon.classes }}</v-icon>
      </v-btn>
    </v-layout>
  </v-footer>
</template>

<script>
export default {
  data() {
    return {
      icons: [
        {
          classes: "fab fa-twitter",
          link: "https://twitter.com/_EdwardBarton"
        },
        {
          classes: "fab fa-linkedin",
          link: "https://www.linkedin.com/in/edwardbarton1/"
        },
        {
          classes: "fab fa-github",
          link: "https://github.com/EdwardBarton"
        }
      ]
    };
  }
};
</script>

<style lang="scss" scoped></style>
