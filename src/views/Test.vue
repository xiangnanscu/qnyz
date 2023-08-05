<template>
  <page-layout>
    <h1 class="center">Test页面</h1>
    <navigator
      url="/views/tabbar/Home"
      open-type="switchTab"
      hover-class="navigator-hover"
    >
      <button>返回首页</button>
    </navigator>
  </page-layout>
</template>

<script>
export default {
  setup(props) {},
  watch: {},
  data() {
    return {};
  },
  async onLoad() {},
  onUnload() {
    console.log("Home onUnload");
  },
  computed: {},
  async onShow() {},
  methods: {}
};
</script>

<style scoped>
.center {
  text-align: center;
}
</style>
