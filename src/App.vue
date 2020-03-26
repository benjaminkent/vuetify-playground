<template>
  <v-app>
    <v-app-bar app color="primary" dark>
      <div>
        <h2>
          Testing Vuetify
        </h2>
      </div>
    </v-app-bar>

    <v-content>
      <router-view />
    </v-content>
  </v-app>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  setup() {
    return {}
  },
})
</script>
