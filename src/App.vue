<template>
  <Index />
</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component'
import Index from './views/Index.vue'

@Options({
  components: {
    Index
  },
})
export default class App extends Vue {}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
