<template>
  <div class="home">
    <v-app id="inspire">
    <Menu></Menu>
    <SlideContents></SlideContents>
    </v-app>

  </div>
</template>

<script>

import Menu from '@/components/Menu.vue'
import SlideContents from '@/components/SlideContents.vue'

export default {
  name: 'Home',
  components: {
    Menu,
    SlideContents,
  }
}
</script>
