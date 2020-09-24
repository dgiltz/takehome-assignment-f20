<template>
  <!-- PART 4: Add your code here -->
  <div>
    <p> Name: {{name}} <Counter v-bind:num=this.episodes_seen></Counter> </p>
  </div>
</template>

<script>
// PART 4: Add your code here
import Counter from "./Counter.vue";

export default {
  props: {
    'id': Number,
    'name': String,
    'episodes_seen': Number
  },
  components: {Counter}, 
};
</script>

<style>
</style>
