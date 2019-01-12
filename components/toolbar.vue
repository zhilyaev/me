<template>
  <v-toolbar app>
    <v-toolbar-title />
    <v-toolbar-items class="hidden-sm-and-down">
      <v-btn
        to="/"
        flat
      >
        <v-icon>fas fa-gem</v-icon>
      </v-btn>
      <v-btn
        to="/skills"
        flat
      >
        <v-icon>fas fa-brain</v-icon>
      </v-btn>
      <v-btn
        to="/timeline"
        flat
      >
        <v-icon>fas fa-rocket</v-icon>
      </v-btn>
    </v-toolbar-items>
  </v-toolbar>
</template>

<script>
export default {
  name: 'Toolbar'
}
</script>

<style scoped>

</style>
