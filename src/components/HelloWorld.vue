<script  lang="ts">
export default {
  props: {
    msg: String
  }
}
</script>

<template>
<div class="hello-world">Shared  {{ msg  }}</div>
</template>

<style scoped  lang="scss">
$primary: #ff9900;
.hello-world {
  background: $primary;
}
</style>
