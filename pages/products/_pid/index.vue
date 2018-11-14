<template>
  <div>
    <h1>PID Page</h1>
    <p>ID of this page: {{ pid }}</p>
  </div>
</template>

<script>
export default {
  computed: {
    pid() {
      return this.$route.params.pid;
    }
  }
}
</script>
