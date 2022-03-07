<template>
  <v-app>
    <v-main>
      <HelloWorld/>
      <v-tabs>
        <v-tab>tab 1</v-tab>
        <v-tab>tab 2</v-tab>
      </v-tabs>
    </v-main>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',

  components: {
    HelloWorld,
  },

  data: () => ({
    //
  }),
}
</script>
