<template>
  <div id="app">
    <mheader></mheader>
    <tab></tab>
    <route-view></route-view>
  </div>
</template>

<script type="text/ecmascript-6">
import Mheader from 'components/m-header/m-header'
import Tab from 'components/tab/tab'
export default {
  components: {
    Mheader,
    Tab
  }
}
</script>

<style scoped lang="stylus" rel="stylesheet/stylus">
  @import "~common/stylus/variable.styl"
#app {
  color: $color-theme
}
</style>
