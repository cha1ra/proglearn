<template>
  <v-parallax dark src="https://cdn.vuetifyjs.com/images/backgrounds/vbanner.jpg">
    <v-layout align-center column justify-center>
      <h1 class="display-2 font-weight-thin mb-3">ProgLearn</h1>
      <prog-learn-logo/>
      <h4 class="subheading">Learn Programming</h4>
    </v-layout>
  </v-parallax>
</template>

<script>
import ProgLearnLogo from "~/components/ProgLearnLogo.vue";

export default {
  components: {
    ProgLearnLogo
  }
};
</script>