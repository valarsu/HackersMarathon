<template>
  <div class="demo-container">
    <div class="phone-container">
      <div class="project-container">
        手机内部显示<br/><br/><br/><br/><br/><br/><br/><br/><br/><br/>手机内部显示<br/>手机内部显示<br/>手机内部显示<br/>手机内部显示<br/>手机内部显示<br/>
      </div>
    </div>
  </div>
</template>

<script>

export default {
  name: 'mobileDemo',
  data () {
    return {}
  }
}
</script>

<style lang="stylus" scoped>
.demo-container
  position absolute
  z-index 1000
  top 0
  left 67%
  bottom 0px
  width 27%
  height 100vh
  padding 1vh 0
.phone-container
  width 100%
  height 100%
  background-image url('../assets/phoneBackground.png')
  background-size 100% 98%
  background-repeat no-repeat
.project-container
  position relative
  width 90%
  height 77%
  overflow auto
  top 10%
  left 5%
  background #ffffff
  border-radius 1%
</style>
