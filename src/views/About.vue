<template>
  <div class="text-center ma-2">
    <v-btn
      dark
      @click="snackbar = true"
    >
      Open Snackbar
    </v-btn>
    <v-snackbar
      v-model="snackbar"
    >
      {{ text }}

      <template v-slot:action="{ attrs }">
        <v-btn
          color="pink"
          text
          v-bind="attrs"
          @click="snackbar = false"
        >
          Close
        </v-btn>
      </template>
    </v-snackbar>
    <Snackbar/>
    <Snackbar2/>
  </div>
</template>

<script>
import Snackbar from '../components/Snackbar/Snakbar.vue'
import Snackbar2 from '../components/Snackbar2/Snackbar2.vue'
  export default {
    components:{
Snackbar,
Snackbar2
    },
    data: () => ({
      snackbar: false,
      text: `Hello, I'm a snackbar`,
    }),
  }
</script>
