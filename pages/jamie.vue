<template>
  <div>
    <h2>{{ message }}</h2>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'JamieHelloWorld',
  data() {
    return {
      message: 'Hello World'
    }
  }
})
</script>
