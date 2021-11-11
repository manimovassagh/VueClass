<template>
  <v-app>
    <v-container>
      <router-link to="/">Home</router-link>
      <router-link to="/about">About</router-link>
      <router-link to="/pedex">pedex</router-link>
      <router-link to="/cc">CC</router-link>
    </v-container>
    <v-main>
      <router-view />
    </v-main>
  </v-app>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  name: "App",
  components: {},
  data: () => ({
    //
  }),
});
</script>
