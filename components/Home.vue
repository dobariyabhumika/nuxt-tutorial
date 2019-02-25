<template>
  <b-container class="main-content">
    <div>
      <!-- <app-logo/> -->
      <h1 class="title">
        Google Play Store
      </h1>
      <h2 class="subtitle">
        Apps with reviews
      </h2>
      <div class="links">
        <a
          href="/apps"
          class="button--green">Apps</a>
        <a
          href="/reviews"
          class="button--grey">Reviews</a>
      </div>
    </div>
  </b-container>
</template>

<script>

  export default {
    name: 'Index',
    components: {
    }
  }
</script>

<style>
.main-content {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
