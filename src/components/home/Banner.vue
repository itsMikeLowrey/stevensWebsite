<template>
  <base-card dark>
    <v-img
      class="grey lighten-2"
      height="400"
      width="100%"
      :src="require(`@/assets/banner.jpg`)"
    >
      <v-layout
        fill-height
        align-center
        pa-3
      >
        <v-flex
          xs5
          md5
          offset-xs6
          offset-md6
          style="background-color:rgba(67, 171, 245, 0.5)"
        >
          <h1 class="display-3 font-weight-light">
            Raising The Barr
          </h1>
          <div class="subheading text-uppercase pl-2 mb-4">
            A Modern Jack of All Trades
          </div>
        </v-flex>
      </v-layout>
    </v-img>
  </base-card>
</template>
