<template>
  <!-- 组件的结构 -->
  <div>
    <h2>学校名称：{{ name }}</h2>
    <h2>学校地点：{{ address }}</h2>
    <button @click="showName">点我提示学校名</button>
  </div>
</template>

<script>
// 组件交互相关的代码（数据 方法等等）
export default {
  name: "School",
  data() {
    return {
      name: "邵阳职业",
      address: "邵阳",
    }
  },
  methods: {
    showName() {
      console.log(this.name, this);
    },
  },
}
</script>

<style>
/* 组件的样式 */
</style>