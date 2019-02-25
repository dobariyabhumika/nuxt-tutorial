<template>
  <b-container>
    <div>
      <b-button variant="info" class="add-app-btn">Add Review</b-button>
      <b-table responsive striped hover :items="reviewData" />
    </div>
  </b-container>
</template>

<script>
  import jsondata from '../static/json-data/reviews-data.json';

  export default {
    name: 'Index',
    components: {
    },
    data() {
      return {
        reviewData: jsondata
      }
    }
  }
</script>

<style>

.add-app-btn {
  margin: 15px 0;
  float: right
}

</style>
