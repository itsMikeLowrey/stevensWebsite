<template>
  <div id="home">
    <v-layout>
  <v-flex xs12 sm10 offset-sm1>
    <p class="display-4 mt-5" style="color:#0365AB;">Startrek Scene Build</p>

    <p style="font-size: 20px;"> Did a Local Job that involved Lorem ipsum dolor sit amet, consectetur adipiscing elit,
       sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim
       veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
        Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat
        nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia
        deserunt mollit anim id est laborum.
    </p>

        <v-container fluid grid-list-sm>
          <v-layout row wrap>
            <v-flex xs6>
              <img src="@/assets/startrek/historywall.jpg" class="image" alt="lorem" width="100%" height="100%">
            </v-flex>
            <v-flex xs6>
              <img src="@/assets/startrek/captaincourters.jpg" class="image" alt="lorem" width="100%" height="100%">
            </v-flex>
            <v-flex xs6>
              <img src="@/assets/startrek/entrance.jpg" class="image" alt="lorem" width="100%" height="100%">
            </v-flex>
            <v-flex xs6>
              <img src="@/assets/startrek/obelski.jpg" class="image" alt="lorem" width="100%" height="100%">
            </v-flex>
            <v-flex xs6>
              <img src="@/assets/startrek/sickbay.jpg" class="image" alt="lorem" width="100%" height="100%">
            </v-flex>
            <v-flex xs6>
              <img src="@/assets/startrek/transportroom.jpg" class="image" alt="lorem" width="100%" height="100%">
            </v-flex>
            <v-flex xs6>
              <img src="@/assets/startrek/turntable.jpg" class="image" alt="lorem" width="100%" height="100%">
            </v-flex>
          </v-layout>
        </v-container>
  </v-flex>
</v-layout>
  </div>
</template>

<script>
  export default {
    name: 'startrek'
  }
</script>
<style scoped>

</style>
