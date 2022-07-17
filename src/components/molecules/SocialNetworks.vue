<template>
  <div class="social-networks">
    <social-link name="GitHub" to="https://github.com" icon="github.svg" />
    <social-link name="twitter" to="https://twitter.com" icon="twitter.svg" />
    <social-link
      name="facebook"
      to="https://facebook.com"
      icon="facebook.svg"
    />
  </div>
</template>

<script>
import { SocialLink } from '@/components/atoms'
export default {
  components: { SocialLink }
}
</script>

<style lang="scss" scoped>
.social-networks {
  display: grid;
  grid-gap: 1rem;
}
</style>
