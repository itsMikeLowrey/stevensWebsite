<template>
  <v-container pa-0>
    <base-subheading>Tags</base-subheading>
    <v-chip
      tag
      label
      small
      color="secondary"
      text-color="white"
    >
      Art
    </v-chip>
    <v-chip
      tag
      label
      small
      color="secondary"
      text-color="white"
    >
      Family
    </v-chip>
    <v-chip
      tag
      label
      small
      color="secondary"
      text-color="white"
    >
      Philosophy
    </v-chip>
  </v-container>
</template>

<script>
  // Utilities
  import {
    mapGetters
  } from 'vuex'

  export default {
    computed: {
      ...mapGetters(['categories'])
    }
  }
</script>
