<template>
  <section class="container">
      <div>
          <Counter />
          <hr>
          <Counter />
          <hr>
          <Counter />
          <hr>
      </div>
  </section>
</template>

<script>
import Counter from '~/components/Counter.vue'

export default {
    components: {
        Counter
    }
}
</script>
