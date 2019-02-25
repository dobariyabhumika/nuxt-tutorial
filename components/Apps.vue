<template>
  <b-container>
    <div>
      <b-button variant="info" class="add-app-btn">Add App</b-button>
      <b-table responsive striped hover :items="appData" />
    </div>
  </b-container>
</template>

<script>
  import jsondata from '../static/json-data/app-data.json';

  export default {
    name: 'Index',
    components: {
    },
    data() {
      return {
        appData: jsondata
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
