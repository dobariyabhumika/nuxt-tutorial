<template>
  <div>
    <Navbar />
    <Apps />
  </div>
</template>

<script>

import Apps from '~/components/Apps.vue'
import Navbar from '~/components/Navbar.vue'

export default {
  components: {
    Apps,
    Navbar
  }
}
</script>

