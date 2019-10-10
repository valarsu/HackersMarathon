<template>
  <div class="demo-container">
    <div class="phone-container">

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
  left 70%
  bottom 0px
  width 30%
  height 100vh
  padding 1vh 0
.phone-container
  width 100%
  height 100%
  background-image url('../assets/phoneBackground.png')
  background-size 100% 98%
  background-repeat no-repeat
</style>
