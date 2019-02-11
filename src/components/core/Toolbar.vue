<template>
  <v-toolbar
    app
    flat
  >
    <v-container
      mx-auto
      py-0
    >
      <v-layout>
        <v-img
          :src="require('@/assets/logo.png')"
          class="mr-5"
          contain
          height="48"
          width="48"
          max-width="48"
        />
        <v-btn
          class="ml-0 hidden-sm-and-down"
          flat
        >
          Home
        </v-btn>
        <v-btn
          class="ml-0 hidden-sm-and-down"
          flat
        >
          Blog
        </v-btn>
        <v-btn
          class="ml-0 hidden-sm-and-down"
          flat
        >
          Shop
        </v-btn>
        <v-btn
          class="ml-0 hidden-sm-and-down"
          flat
        >
         Consultations
        </v-btn>
        <v-btn
          class="ml-0 hidden-sm-and-down"
          flat
        >
         portfolio
        </v-btn>
        <v-spacer />
        <!-- <v-text-field
          append-icon="mdi-magnify"
          flat
          hide-details
          solo-inverted
          style="max-width: 300px;"
        /> -->
      </v-layout>
    </v-container>
  </v-toolbar>
</template>

<script>
  // Utilities
  import {
    mapGetters,
    mapMutations
  } from 'vuex'

  export default {
    computed: {
      ...mapGetters(['links'])
    },

    methods: {
      ...mapMutations(['toggleDrawer']),
      onClick (e, item) {
        e.stopPropagation()

        if (item.to || !item.href) return

        this.$vuetify.goTo(item.href)
      }
    }
  }
</script>
