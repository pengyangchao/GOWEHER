<template>
<div class='header'>
  <div class='header-left'>
    <span class="iconfont">&#xe624;</span>
  </div>
  <div class='header-input'>
    <span class="iconfont">&#xe632;</span>
  </div>
  <div class='header-right'>城市
    <span class="iconfont">&#xe64a;</span>
  </div>
</div>
</template>

<script>
export default {
  name: 'HomeHeader'
}
</script>

<style lang='stylus' scoped>
  @import '~styles/varibles.styl';
  .header
    display flex
    flex-directio row
    line-height .86rem
    background-color $bgColor
    color #fff
  .header-left
    width .64rem
    text-align center
  .header-input
    flex 1
    background-color #fff
    margin-top .12rem
    margin-left .2rem
    height .64rem
  .header-right
    width 1.24rem
    text-align center
</style>
