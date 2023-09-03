<script>
import FirstMainSection from './FirstMainSection.vue';
import SecondMainSection from './SecondMainSection.vue';
import ThirdMainSection from './ThirdMainSection.vue';
import FourthMainSection from './FourthMainSection.vue';
import FifthMainSection from './FifthMainSection.vue'
import SixthMainSection from './SixthMainSection.vue';
export default {
  components: {
    FirstMainSection,
    SecondMainSection,
    ThirdMainSection,
    FourthMainSection,
    FifthMainSection,
    SixthMainSection
  }
}
</script>

<template>
  <FirstMainSection></FirstMainSection>
  <SecondMainSection></SecondMainSection>
  <ThirdMainSection></ThirdMainSection>
  <FourthMainSection></FourthMainSection>
  <FifthMainSection></FifthMainSection>
  <SixthMainSection></SixthMainSection>
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables.scss' as *;
@use '../styles/partials/utilities.scss' as *;
</style>