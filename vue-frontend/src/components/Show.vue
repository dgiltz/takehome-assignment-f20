<script>
// PART 4: Add your code here
import Counter from "./Counter.vue";

export default {
  props={
    'id': Number,
    'name': String,
    'episodes_seen': Number
  },
  components: {Counter}, 
};
</script>

<style>
</style>
