<template>
  <div class="services">
    <Service
      title="Front End"
      description="Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusantium iusto cum, dolorem quas cumque illo quam alias saepe repellat reiciendis, suscipit rerum tempore error, quo placeat distinctio consequuntur porro labore."
    />
    <Service
      title="Back end"
      description="Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusantium iusto cum, dolorem quas cumque illo quam alias saepe repellat reiciendis, suscipit rerum tempore error, quo placeat distinctio consequuntur porro labore."
    />
    <Service
      title="Manutenção"
      description="Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusantium iusto cum, dolorem quas cumque illo quam alias saepe repellat reiciendis, suscipit rerum tempore error, quo placeat distinctio consequuntur porro labore."
    />
  </div>
</template>

<script>
import { Service } from '@/components/molecules'
export default {
  components: { Service }
}
</script>

<style lang="scss" scoped>
.services {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 5rem;
}
</style>
