<template>
  <v-app dark>
    <left />
    <toolbar />
    <v-content>
      <v-container>
        <nuxt />
      </v-container>
    </v-content>
    <myfooter />
  </v-app>
</template>

<script>
import myfooter from '~/components/myfooter'
import left from '~/components/left'
import Toolbar from '../components/toolbar'
export default {
  components: { Toolbar, left, myfooter }
}
</script>
