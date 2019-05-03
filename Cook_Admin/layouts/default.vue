<template>
  <v-app dark>
      <Toolbar/>
    <v-content>
      <v-container>
        <nuxt />
      </v-container>
    </v-content>

    <Footer/>
  </v-app>
</template>

<script>
import Toolbar from '@/components/core/toolbar'
import Footer from '@/components/core/footer'

export default {
  components: {
    Toolbar,
    Footer
  },
  data () {
    return {

    }
  }
}
</script>
