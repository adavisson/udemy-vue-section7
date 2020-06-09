<template>
  <div>
    <app-server-status v-for="server in 5" v-bind:key="server" />
  </div>
</template>

<script>
import ServerStatus from './ServerStatus'

export default {
  components: {
    'app-server-status': ServerStatus
  }
}
</script>

<style scoped>
</style>