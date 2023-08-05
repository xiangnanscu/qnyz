<template>
  <page-layout>
    <h1 class="center">祝贺!小伙子,你成功运行UNIAPP了</h1>
    <p class="center">从此你将踏进小程序开发的快车道</p>
    <p class="center">向韬书记秀下你的肌肉吧</p>
    <navigator
      url="/views/Uform"
      open-type="navigate"
      hover-class="navigator-hover"
    >
      <button>点击跳转到Uform</button>
    </navigator>
    <navigator
      url="/views/Test"
      open-type="navigate"
      hover-class="navigator-hover"
    >
      <button>点击跳转到Test</button>
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
