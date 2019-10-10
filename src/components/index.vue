<template>
  <div class="page-container">
    <full-page ref="fullpage" :options="options" id="fullpage">
      <div class="section">
        <h1>第一页</h1>
        <h1>Index.vue写ppt内容</h1>
        <h1>子路由配置功能页</h1>
        <h1>app.vue中，把手机框固定定位在右侧</h1>
        <h1>{{ msg }}</h1>
      </div>
      <div class="section">
        <h1>第二页</h1>
        <h1>{{ msg }}</h1>
      </div>
    </full-page>
    <mobile-demo>
      <router-view></router-view>
    </mobile-demo>
  </div>
</template>

<script>
import MobileDemo from '../fragment/mobileDemo.vue'
export default {
  name: 'index',
  data () {
    return {
      msg: 'A project that includes a video streaming and queuing system',
      options: {
        licenseKey: 'YOUR_KEY_HEERE',
        anchors: ['/list', '/detail'],
        sectionsColor: '#fff'
      }
    }
  },
  components: {
    MobileDemo
  }
}
</script>

<style lang="stylus" scoped>
.page-container
  position absolute
</style>
