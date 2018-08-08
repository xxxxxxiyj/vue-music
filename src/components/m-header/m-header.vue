<template>
  <div class="m-header">
    <div class="icon"></div>
    <!-- <div class="text">下载APP</div> -->
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
    background-color: $color-theme
    .icon
      display: inline-block
      margin-top: .2rem
      width: 1.8rem
      height: .5rem
      background: url('./logo.png') no-repeat
      background-size: cover
    .text
      display: inline-block
      vertical-align: top
      line-height: .88rem
      font-size: $font-size-large
</style>
