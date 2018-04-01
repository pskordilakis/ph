<template>
  <div>
    <span>{{counter}}</span>
    <button @click="increase">CLick Me</button>
  </div>
</template>
<script>
export default {
  data() {
    return {counter:0}
  },
  methods: {
    increase() {
      this.counter++
    }
  }
}
</script>
