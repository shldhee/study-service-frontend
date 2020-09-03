<template>
  <div>
    <v-app-bar app color="primary" dark>
      <router-link to="/">
        <v-btn>Blog Posting Admin</v-btn>
      </router-link>
      <v-spacer></v-spacer>
      <router-link to="/sign-in"><v-btn>Sign In</v-btn></router-link>
    </v-app-bar>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';

@Component
export default class extends Vue {}
</script>

<style scoped></style>
