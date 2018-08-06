<template>
  <div class="m-header">
    <div class="icon"></div>
    <div class="text">Music</div>
  </div>
</template>

<script>
export default {
}
</script>

<style lang="stylus" scoped>
  @import "~common/stylus/variable"
  @import "~common/stylus/mixin"
  .m-header
    position: relative
    height: .88rem
    text-align: center
    font-size: 0
    color: $color-theme
    .icon
      display: inline-block
      margin-top: .12rem
      margin-right: .18rem
      width: .6rem
      height: .64rem
      bg-image('logo')
      background-size: .6rem .64rem
    .text
      display: inline-block
      vertical-align: top
      line-height: .88rem
      font-size: $font-size-large
</style>
