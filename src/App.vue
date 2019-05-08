<template>
  <v-app>
    <v-toolbar app class="info white--text" flat>
      <v-toolbar-title class="headline text-uppercase">
        <span>Locker DUDE</span>
        <span class="font-weight-light"> SUPER EPIC GAMER DESIGN</span>
      </v-toolbar-title>
      <v-spacer></v-spacer>
      <v-btn
        flat
        href="https://github.com/vuetifyjs/vuetify/releases/latest"
        target="_blank"
      >
        <span class="white--text mr-2">Latest Release</span>
      </v-btn>
    </v-toolbar>

    <v-content>
      <HelloWorld/>
    </v-content>
    <v-footer height="auto" color="success"> <v-layout> <v-flex ys12>
      Epic
      <v-spacer></v-spacer>
      <v-btn fab color="info">
          <v-icon>add_to_queue</v-icon>
      </v-btn> </v-flex> </v-layout> 
    </v-footer>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld'

export default {
  name: 'App',
  components: {
    HelloWorld
  },
  data () {
    return {
      //
    }
  }
}
</script>
