<template>
  <div>
    <h1>{{message}}</h1>
    <button @click="handleClick">button</button>
  </div>
</template>

<script>
export default {
  data () {
    return {
      message: 'I am LiBin'
    }
  },
  methods: {
    handleClick() {
      alert("你点了我一下");
    }
  }
}
</script>

<style scoped>
</style>
