<template>
  <div>
    <p>I'm a Counter!</p>
    <Counter v-bind:num='0'></Counter>
    <p>The count is {{count}}</p>
    <div>
      <button v-on:click="count++">Increase</button>
      <button v-on:click="count--">Decrease</button>
    </div>
  </div>
</template>

<script>
export default {
  props: {'num': Number},
  data() {
    return {
      count: this.num
    };
  },
};
</script>

<style>
</style>
