<template>
  <!-- PART 4: Add your code here -->
  <div>
  <Counter v-bind:num=this.episodes_seen>
    <p> Name: {{name}} {{count}}</p>
  </Counter>
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
