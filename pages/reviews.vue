<template>
  <div>
    <Navbar />
    <Reviews />
  </div>
</template>

<script>

import Reviews from '~/components/Reviews.vue'
import Navbar from '~/components/Navbar.vue'

export default {
  components: {
    Reviews,
    Navbar
  }
}
</script>

