<template>
  <a :href="to" class="nav-item">
    {{ text }}
  </a>
</template>

<script>
export default {
  props: {
    text: { type: String, required: true },
    to: { type: String, required: true }
  }
}
</script>

<style lang="scss" scoped>
.nav-item {
  color: #293947;
  text-decoration: none;
  font-size: 1.3rem;
}
</style>
