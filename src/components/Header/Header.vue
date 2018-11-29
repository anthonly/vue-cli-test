<template>
  <div class="header">
    <span class="iconfont icon-xiangzuojiantou headerLeft"></span>
    <div class="headerCenter"><span class="iconfont icon-search headerSearch">输入城市/景点/游玩主题</span></div>
    <div class="headerRight">北京 <span class="iconfont icon-sanjiao_xia"></span></div>
  </div>
</template>
<script>
  export default {
    name: 'Header'
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="stylus">
  .header
    height:.44rem; display: flex; background-color :#00bcd4; justify-content :space-between;box-sizing :border-box;
    .iconfont
      color:white;line-height:.44rem;
    .headerRight
      font-size:.14rem;line-height:.44rem;color:white;padding:0 .02rem 0 0;
    .headerLeft
      display: block;width:.2rem;padding:0 .1rem;
    .headerCenter
      width:3.74rem;height:.30rem;background-color :white;margin-top:.07rem;border-radius :.05rem;
      padding-left:.1rem;box-sizing :border-box;
    .headerSearch
      color: #e4e7ea;line-height:1;
</style>
