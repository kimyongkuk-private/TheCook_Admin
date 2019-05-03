<template>
  <v-app dark>
      <Toolbar/>
    <v-content>
      <v-container>
        <nuxt />
      </v-container>
    </v-content>

    <v-footer :fixed="fixed" app>
      <span>&copy; {{ new Date().getFullYear() }}</span>
    </v-footer>
  </v-app>
</template>

<script>
import Toolbar from '@/components/core/toolbar'

export default {
  components: {
    Toolbar
  },
  data () {
    return {

    }
  }
}
</script>
