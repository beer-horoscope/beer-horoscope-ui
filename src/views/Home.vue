<template>
  <div class="home">
    <p>HI, NEW CHANGES</p>
    <BeerRecForm></BeerRecForm>
  </div>
</template>

<script>

import BeerRecForm from '@/components/BeerRecForm.vue'

export default {
  name: 'Home',
  components: {
    BeerRecForm
  }
}
</script>
