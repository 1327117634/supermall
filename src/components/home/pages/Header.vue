<template>
<div class="header">
  <div class="header-left">
    <span class="iconfont">&#xe624;</span>
  </div>
  <div class="header-search">
    <span class="iconfont">&#xe632;</span>
    输入城市、景点、游玩主题
  </div>
  <div class="header-right">
    北京
    <span class="iconfont">&#xe64a;</span>
  </div>
</div>
</template>

<script>

</script>

<style scoped >

.header{
  width: 100%;
  height:.88rem;
  background:#00bcd4;
  color:#fff;
  font-size:.36rem;
  display: flex;
}
.header-left{
  width:.6rem;
  padding:.2rem .1rem;
  text-align: center;
  font-weight: bold;
  line-height: .5rem;
}
.header-right{

  padding:.2rem;
  text-align: center;
  font-size: .28rem;
  line-height: .5rem;
}
.header-search{
  flex:1;
  background: #fff;
  height:.6rem;
  margin:.14rem 0;
  border-radius: .1rem;
  color:#e4e7ea;
  line-height: .6rem;
  font-size: .28rem;
  padding-left: .2rem;
}

</style>
