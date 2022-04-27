<template>
  <div id="HomeView">
    <ToolBar />
    <PokeCards />
  </div>
</template>

<script>
import ToolBar from '@/components/ToolBar.vue';
import PokeCards from '@/components/PokeCards.vue';
export default {
  name: 'HomeView',
  components: {
    ToolBar,
    PokeCards,
  }
}
</script>
