<script>
import { RouterLink, RouterView } from "vue-router";
import Vmodel from "../components/VtextAndVModel.vue";

export default {
  data() {
    return {};
  },
  components: {
    RouterLink,
    RouterView,
    Vmodel,
  },
};
</script>

<template>
  <div class="box">
    <h1>歡迎來到商店頁面</h1>
  </div>
  <Vmodel></Vmodel>
</template>

<style scoped lang="scss">
.box {
  background-color: black;
  color: white;
  display: flex;
  flex-direction: column;
  align-items: center;

  h1 {
    font-size: 2rem;
  }

  p {
    font-size: 1.15rem;
  }
}
</style>
