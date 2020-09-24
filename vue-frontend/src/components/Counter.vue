<template>
  <div>
    <Counter :num=''0''></Counter>
    <p>{{count}}</p>
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
