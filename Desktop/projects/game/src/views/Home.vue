<template lang="pug">
  b-container 
    silder
    b-row
        popular
    b-row
      looking
    b-row 
      trusted
    b-row 
      advice
    foot
</template>

<script>
// @ is an alias to /src
import silder from '../components/landing Components/silder.vue'
import popular from '../components/landing Components/popular.vue'
import looking from '../components/landing Components/Looking.vue'
import trusted from '../components/landing Components/trusted.vue'
import advice from '../components/landing Components/advice.vue'
import foot from '../components/footer.vue'
export default {
  name: 'Home',
  components: {
    silder,
    popular,
    looking,
    trusted,
    advice,
    foot
  }
}
</script>
