<script></script>

<template>
  <div class="navBar">
    <RouterLink to="/" class="link">首頁| </RouterLink>
    <RouterLink to="/about" class="link"> 關於| </RouterLink>
    <RouterLink to="/footer" class="link"> Footer| </RouterLink>
    <RouterLink to="/shop" class="link"> 商店| </RouterLink>
  </div>
  <RouterView />
</template>

<style lang="scss" scoped>
.navBar {
  display: flex;
  justify-content: space-around;
  align-items: center;
  background-color: #777;
  height: 3rem;

  .link {
    text-decoration: none;
    color: white;
    font-size: 1.5rem;
    border-radius: 8px;
    transition: all 0.5s ease;

    &:hover {
      border: 3px solid white;
      color: black;
    }
  }
}
</style>
