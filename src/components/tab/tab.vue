<template>
  <div class="tab">
    <router-link class="tab-item" to="/recommend">
      <span class="tab-link">推荐</span>
    </router-link>
    <router-link class="tab-item" to="/singer">
      <span class="tab-link">歌手</span>
    </router-link>
    <router-link class="tab-item" to="/rank">
      <span class="tab-link">排行</span>
    </router-link>
    <router-link class="tab-item" to="/search">
      <span class="tab-link">搜索</span>
    </router-link>
  </div>
</template>

<script>
export default {
}
</script>

<style lang="stylus" scoped>
  @import "~common/stylus/variable"
  .tab
    display: flex
    flex-direction: row
    height: .88rem
    line-height: .88rem
    font-size: $font-size-medium
    .tab-item
      flex: 1
      text-align: center
      .tab-link
        padding-bottom: .1rem
        letter-spacing: .05rem
        color: $color-text-l
      &.router-link-active
        .tab-link
          color: $color-theme
          border-bottom: 2px solid $color-theme
</style>
