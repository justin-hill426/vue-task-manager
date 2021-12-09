<template>
  <nav>
    <v-toolbar flat app>
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
  </nav>
</template>

<script>
  export default {
    name: 'NavBar',
    data() {
      return {

      }
    }
  }
</script>

<style lang="scss" scoped>

</style>