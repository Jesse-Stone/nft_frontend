<template>
  <v-app class="green darken-4">
    <Navbar />
    <v-content>
      <router-view></router-view>
    </v-content>
  </v-app>
</template>

<script>

import Navbar from '../src/components/Navbar.vue'

export default {
  name: 'App',
  components: {Navbar},

  data: () => ({
    //
  }),
};
</script>
