<template>
  <div id="app">
    <Flow />
  </div>
</template>

<style lang="scss">

</style>


<script>

import Flow from './qux/Flow.vue'
import Logger from './qux/Logger'

export default {
  name: 'App',
  components: {
    Flow: Flow
  },
  mounted () {
    Logger.setLogLevel(5)
  }
}
</script>


