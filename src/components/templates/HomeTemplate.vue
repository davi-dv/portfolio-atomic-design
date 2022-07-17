<template>
  <Container class="home-template">
    <Header />
    <Presentation />
    <Services />
  </Container>
</template>

<script>
import { Container } from '@/components/bosons'
import { Header, Presentation, Services } from '@/components/organisms'
export default {
  components: { Container, Header, Presentation, Services }
}
</script>

<style lang="scss" scoped>
.home-template {
  margin: 5rem auto;
  display: grid;
  grid-gap: 5rem;
}
</style>
