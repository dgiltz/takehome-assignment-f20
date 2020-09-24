<template>
  <div>
    <p>I'm a Counter!</p>
    <p>The count is {{count}}</p>
    <div>
      <button v-on:click="count++">Increase</button>
      <button v-on:click="count--">Decrease</button>
    </div>
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
  template: '<button v-on:click="count++">Increase</button>', 
  template: '<button v-on:click="count--">Decrease</button>'
};
</script>

<style>
</style>
