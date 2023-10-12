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
  <h1 class="title">首頁內容</h1>
  <h1>這是首頁標題</h1>
  <p>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis modi
    deserunt dicta hic quisquam repellendus autem, corrupti temporibus voluptate
    illo!
  </p>
</template>

<style scoped lang="scss">
.title {
  border: 1px solid #777;
}
</style>
