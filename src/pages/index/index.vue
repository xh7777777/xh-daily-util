<template>
  <view class="index">
    <Counter />
    <view>距离下班还有</view>
  </view>
</template>

<script>
import './index.scss'
import Counter from '../../components/Counter.vue'

export default {
  name: 'Index',
  components: {
    Counter
  }
}
</script>
