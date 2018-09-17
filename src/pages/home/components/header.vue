<template>
  <div class='header'>
    <div class="header-left">
      <div class="iconfont back-icon">&#xe624;</div>
    </div>
    <div class="header-input">
      <span class="iconfont">&#xe632;</span>
      输入城市/景点/游玩主题
    </div>
    <div class="header-right">
      城市
      <span class="iconfont arrow-icon">&#xe6aa;</span>
    </div>
  </div>
</template>

<script>
export default {
  name: "HomeHeader"
};
</script>

<style lang='stylus' scoped>
@import '../../../assets/styles/varibles.styl'
.header
  display flex
  height:0.86rem
  line-height .86rem
  color white
  background:$bgColor
  .header-left
    .back-icon
      text-align: center
      font-size: 0.3rem
    width:0.64rem
    float:left
  .header-right
    width:1.24rem
    font-size: 0.3rem
    .arrow-icon
      font-size: .35rem
      margin-left: -0.05rem
  .header-input
    padding-left: .2rem
    flex:1
    background #ffffff
    border-radius .1rem
    margin-top 0.12rem
    margin-bottom  0.12rem
    margin-left 0.2rem
    margin-right 0.1rem
    color:#ccc
    line-height 0.62rem
</style>
