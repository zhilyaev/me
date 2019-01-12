<template>
  <v-navigation-drawer
    app
    stateless
    :value="true"
  >
    <v-img
      src="https://avatars3.githubusercontent.com/u/4854707?s=460&v=4"
    >
      <v-layout
        pa-2
        column
        fill-height
        class="lightbox white--text"
      >
        <v-spacer />
        <v-flex shrink>
          <div class="subheading">
            Zhilyaev Dmitriy
          </div>
          <div class="body-1">
            zhilyaev.dmitriy@gmail.com
          </div>
        </v-flex>
      </v-layout>
    </v-img>
  </v-navigation-drawer>
</template>

<script>
export default {
  name: 'Left'
}
</script>

<style scoped>

</style>
