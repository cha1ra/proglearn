<template>
  <v-layout column justify-center align-center>
    <v-flex xs12 sm8 md6>
      <div class="text-xs-center">
        <prog-learn-logo/>
      </div>
      <v-card>
        <v-card-title class="headline">Welcome to ProgLearn.com!</v-card-title>
        <v-card-text>
          <p>ProgLearnではプログラミング学習に役立つツールを提供予定です。</p>
          <p>2019年2月下旬に最初のサービスリリースを予定しています。今しばらくお待ちください。</p>
          <div class="text-xs-right">
            <em>
              <small>どんぶラッコ</small>
            </em>
          </div>
          <hr class="my-3">
          <a href="https://twitter.com/don_bu_rakko">Twitter</a>
          <br>
          <a href="https://qiita.com/don-bu-rakko">Qiita</a>
        </v-card-text>
        <v-card-actions>
          <v-spacer/>
          <v-btn color="primary" flat nuxt to="/codictionary">Continue</v-btn>
        </v-card-actions>
      </v-card>
    </v-flex>
  </v-layout>
</template>

<script>
import Logo from "~/components/Logo.vue";
import VuetifyLogo from "~/components/VuetifyLogo.vue";
import ProgLearnLogo from "~/components/ProgLearnLogo.vue";

export default {
  components: {
    Logo,
    VuetifyLogo,
    ProgLearnLogo
  }
};
</script>
