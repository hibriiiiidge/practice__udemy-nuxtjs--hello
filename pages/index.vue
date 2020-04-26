<template>
  <section>
    <p>{{ message }}</p>
    <hr>
    <router-link to="/price">Price</router-link>
  </section>
</template>

<script>
export default {
  data() {
    return {
      message: 'Hello, World'
    }
  }
}
</script>

<style>
</style>
