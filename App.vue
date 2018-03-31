<template>
  <div>
    {{message}}
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
