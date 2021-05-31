<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
  mpType: 'app',
  //  初始化完成
  onLaunch () {
    console.log('App Launch')
  },
  //  启动，或从后台进入前台显示
  onShow () {
    console.log('App Show')
  },
  // 从前台进入后台
  onHide () {
    console.log('App Hide')
  },
  // 报错时触发
  onError () {
    console.log('App Error')
  },
  methods: {

  }
})
</script>

<style>
/*每个页面公共css */
</style>
