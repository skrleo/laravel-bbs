<template>
  <div class="container">
    <el-menu :default-active="activeIndex" class="el-menu-demo" mode="horizontal" @select="handleSelect">

    </el-menu>
    <view class="hero">
1231
    </view>
  </div>
</template>

<script>
  export default {
    data() {
      return {
        activeIndex: '1',
        activeIndex2: '1'
      };
    },
    methods: {
      handleSelect(key, keyPath) {
        console.log(key, keyPath);
      }
    }
  }
</script>
<style>
  .hero {
      width:100%;
      height:260px;
      display:block;
      margin-top: -1px;
      background: #e4edf6;
      text-align: center;
      color: #667f99;
  }
</style>
