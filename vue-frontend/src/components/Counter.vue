<template>
  <div>
    <p>I'm a Counter!</p>
    <p>The count is <Counter v-bind:num=0>{{count}}</Counter></p>
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
      count: this.props.num
    };
  },
  template: '<p> The count is {{count}} </p>',
  template: '<button v-on:click="count++">Increase</button>', 
  template: '<button v-on:click="count--">Decrease</button>'
};
</script>

<style>
</style>
