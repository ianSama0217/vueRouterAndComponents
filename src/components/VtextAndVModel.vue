<script>
//import商品資訊卡
import card from "../components/StoreCard.vue";

export default {
  name: "Vmodel",
  props: {
    msg: String,
  },
  data() {},
  components: {
    card,
  },
};
</script>

<template>
  <div class="box">
    <h1>這個是組件</h1>
    <p>組件內的資訊: {{ msg }}</p>
  </div>

  <!-- 從StoreCard引入的元件 -->
  <div class="area">
    <card productName="蘋果" productValue="50" />
    <card productName="香蕉" productValue="30" />
    <card productName="哈密瓜" productValue="199" />
  </div>
</template>

<style scoped lang="scss">
.box {
  background-color: aquamarine;
  height: 10rem;
  h1 {
    color: darkgray;
  }
}

.area {
  display: flex;
  justify-content: space-around;
}
</style>
