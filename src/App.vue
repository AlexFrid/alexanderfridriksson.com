<template>
  <v-app>
    <cv></cv>
  </v-app>
</template>


<script>
import cv from './components/cv';

export default {
  name: 'App',
  components: {
    cv,
  },
  data: () => ({
    //
  }),
};
</script>
