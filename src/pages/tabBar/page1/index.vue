<template>
  <view class="content">
    <view>
      <text class="title" @click="toIndex">{{ title }}</text>
    </view>
  </view>
</template>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
  data () {
    return {
      title: 'Hello World'
    }
  },
  onLoad () {
    console.log('onLoad')
  },
  methods: {
    toIndex () {
      console.log(233)
      // eslint-disable-next-line no-undef
      uni.navigateTo({
        url: '/pages/index/index'
      })
    }
  }
})
</script>

<style>

</style>
