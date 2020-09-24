<template>
  <div id='Counter'>
    <p>I'm a Counter!</p>
    <Counter></Counter>
  </div>
</template>

<script>
export default {
  data() {
    return {
      count: 0
    };
  },
  template: '<p>The count is {{count}}</p>',
  //template: '<button v-on:click="count++">Increase</button> <button v-on:click="count--">Decrease</button>'
};
</script>

<style>
</style>
