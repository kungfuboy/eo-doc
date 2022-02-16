<template>
  经过测试，这个页面可以完全由Vue绘制
  <span>{{ count }}</span>
  <button @click="handleClick()">click</button>
</template>

<script>
export default {
  name: "home",
  data: () => ({ count: 0 }),
  methods: {
    handleClick() {
      this.count++;
    },
  },
};
</script>
<style lang="stylus" scoped></style>