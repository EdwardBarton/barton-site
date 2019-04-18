<template>
  <v-container fill-height fluid>
    <v-layout fill-height text-xs-center wrap>
      <Greeting />
      <About />
    </v-layout>
  </v-container>
</template>

<script>
import Greeting from "../components/Greeting";
import About from "../components/About";

export default {
  components: {
    Greeting,
    About
  }
};
</script>

<style>
.container {
  padding: 0;
}
</style>
