<template>
  <div class="home">
    <TheHeader/>
    <ListCard/>
  </div>
</template>

<script>
// @ is an alias to /src
import TheHeader from '@/components/blocks/TheHeader.vue'

import ListCard from '@/components/blocks/ListCards.vue'

export default {
  name: 'HomeView',
  components: {
    TheHeader,
    ListCard
  }
}
</script>
