<template>
  <div id="app">
    <Header></Header>
    <div class="tab">
      <div class="tab-item">商品</div>
      <div class="tab-item">评论</div>
      <div class="tab-item">商家</div>
    </div>
  </div>
</template>

<script>
  // 引入
import Header from './components/header/header.vue';

export default {
  name: 'app',
  components: {
    Header
  }
};
</script>

<style lang="stylus" rel="stylesheet/stylus">
  #app{
    .tab{
      display:flex;
      width:100%;
      height:40px;
      line-height 40px;
      .tab-item{
        flex:1;
        text-align:center;
      }

    }
  }
</style>
