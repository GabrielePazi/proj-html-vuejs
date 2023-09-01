<script>
import TheHeader from './components/TheHeader.vue'
import TheJumbo from './components/TheJumbo.vue'
import TheMain from './components/TheMain.vue'
import TheFooter from './components/TheFooter.vue'
import * as bootstrap from 'bootstrap'

export default {
  components: {
    TheHeader,
    TheJumbo,
    TheMain,
    TheFooter
  }
}
</script>

<template>
  <TheHeader></TheHeader>

  <main>
    <TheJumbo></TheJumbo>
  </main>
</template>

<style lang="scss">


</style>
