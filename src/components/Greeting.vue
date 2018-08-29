<template>
  <div class="greeting">
    <h1 class="text-green">Hi</h1>
    <p class="text-red">Hello</p>
    <p class="text-blue">greeting: {{ greeting('vue') }}</p>
  </div>
</template>

<script>
import greeting from './greeting'

export default {
  data() {
    return {
      greeting
    }
  }
}
</script>

<style>
.text-green {
  color: green;
}
.text-red {
  color: red;
}
</style>
