<template>
  <div class="qux-flow">
    Flow
  </div>
</template>

<style lang="scss">
    @import '../scss/qux-flow.scss';
</style>

<script>
import Logger from './Logger'

export default {
  name: 'QUX-Flow',
  components: {
  },
  mounted () {
    Logger.log(5, 'Flow.mounted()', 'enter')
  }
}
</script>
