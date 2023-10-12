<script>
import { RouterLink, RouterView } from "vue-router";

export default {
  data() {
    return {};
  },
  components: {
    RouterLink,
    RouterView,
  },
};
</script>

<template>
  <div class="box">
    <h1>歡迎來到Footer頁面</h1>
    <p>
      Lorem ipsum dolor, sit amet consectetur adipisicing elit. Voluptas,
      aperiam.
    </p>
  </div>
</template>

<style lang="scss" scoped>
.box {
  border: 1px solid #777;
  margin-top: 2rem;
}
</style>
