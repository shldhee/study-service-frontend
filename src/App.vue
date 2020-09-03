<template>
  <v-app>
    <AppHeader />
    <v-main>
      <router-view></router-view>
    </v-main>
  </v-app>
</template>

<script lang="ts">
import Vue from 'vue';
import Component from 'vue-class-component';
import AppHeader from '@/components/AppHeader.vue';

@Component({
  components: {
    AppHeader,
  },
})
export default class App extends Vue {}
</script>
