<template>
  <div class="copyright-cmp">
    <p class="copyright-item">Copyright©2023-{{endTime}}</p>
    <p class="copyright-item">作者：小志</p>
    <p class="copyright-item">小志QQ：2140030057</p>
    <p class="copyright-item">备用QQ：2797666032</p>
    <p class="copyright-item">小志QQ交流群：894055051</p>
    <p class="copyright-item">温馨提示：版权所有 违者必究</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      endTime: new Date().getFullYear()
    }
  },
}
</script>

<style lang="scss">
.copyright-cmp {
  position: fixed;
  bottom: 40px;
  left: 50%;
  transform: translateX(-50%);
  text-align: center;
  .copyright-item {
    margin: 0 0 5px;
    color: #ffffff;
    font-size: 14px;
  }
}
</style>
