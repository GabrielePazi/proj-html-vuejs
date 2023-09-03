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
    <TheMain></TheMain>
  </main>

  <TheFooter></TheFooter>
</template>

<style lang="scss">
@use './styles/partials/variables.scss' as *;
@use './styles/partials/utilities.scss' as *;

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

main {
  background-color: $bg-header;
}

</style>
