<template>
  <div class="app-container">
    <h1>MarkEditor</h1>
    <div class="editor-container">
      <mark-editor />
    </div>
  </div>
</template>

<script>
import MarkEditor from './MarkEditor'

const name = 'App'

export default {
  name,
  components: { MarkEditor },

}
</script>

<style lang="less" scoped>
  .app-container {
    width: 100%;
    height: 100px;
    text-align: center;
    .editor-container {
      max-width: 1000px;
      height: 800px;
      border: 1px solid gray;
      margin: auto;
    }
  }
</style>
