<template>
  <div id="app">
    <TreeOfLife />
  </div>
</template>

<script>
import Vue from 'vue'
import { TreeOfLife } from '@/entry.esm'

export default Vue.extend({
  name: 'ServeDev',
  components: {
    TreeOfLife
  }
})
</script>
