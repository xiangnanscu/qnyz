<script setup lang="ts">
import { onLaunch, onShow, onHide } from "@dcloudio/uni-app";
onLaunch(() => {
  console.log("App Launch");
});
onShow(() => {
  console.log("App Show");
});
onHide(() => {
  console.log("App Hide");
});
</script>
<style>
/* uni.showModal 格式覆盖 */
.uni-input-input:disabled {
  color: #333333;
}
:deep(.uni-modal__hd) {
  color: black;
}
:deep(.uni-modal__bd) {
  color: black;
}
</style>
