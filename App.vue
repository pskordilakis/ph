<template>
  <div class="container mx-auto">
    <h1 class="text-indigo">{{message}}</h1>
    <counter></counter>
    <counter></counter>
  </div>
</template>
<script>
import Counter from "./Counter"
export default {
  components: {
    Counter
  },
  data() {
    return {message: 'Welcome to PH'}
  }
}
</script>
