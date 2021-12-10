<template>
  <nav>
    <v-toolbar flat app>
      <v-toolbar-side-icon class="grey--text" @click="drawer = !drawer"></v-toolbar-side-icon>
      <v-toolbar-title class="text-uppercase grey--text">
        <span class="font-weight-light">
          Todo-Ninja
        </span>
      </v-toolbar-title>
      <v-spacer></v-spacer>
      <v-btn flat color="grey">
        <span>Sign Out</span>
        <v-icon right>mdi-exit-to-app</v-icon>
      </v-btn>
    </v-toolbar>
    
    <v-navigation-drawer v-model="drawer" app class="indigo">
      <p>Test</p>

    </v-navigation-drawer>
  </nav>
</template>

<script>
  export default {
    name: 'NavBar',
    data() {
      return {
        drawer: false
      }
    }
  }
</script>

<style lang="scss" scoped>

</style>