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
    height: .44rem
    text-align: center
    font-size: 0
    color: $color-theme
    .icon
      display: inline-block
      margin-top: .06rem
      margin-right: .09rem
      width: .3rem
      height: .32rem
      bg-image('logo')
      background-size: .3rem .32rem
    .text
      display: inline-block
      vertical-align: top
      line-height: 44px
      font-size: $font-size-large
</style>
