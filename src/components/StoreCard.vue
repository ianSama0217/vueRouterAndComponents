<script>
export default {
  name: "card",
  props: {
    productName: {
      type: String,
      required: true,
    },
    productValue: {
      type: Number,
      default: 0,
      required: true,
    },
  },
  methods: {
    buy() {
      alert("購買成功!");
    },
  },
};
</script>

<template>
  <div class="cardBox">
    <h3>商品名稱:{{ productName }}</h3>
    <p>商品價格:${{ productValue }}</p>
    <button @click="buy">訂購</button>
  </div>
</template>

<style scoped lang="scss">
.cardBox {
  background-color: aqua;
  border: 2px solid blue;
  padding: 1rem;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  border-radius: 8px;

  h3 {
    font-size: 1.5rem;
  }

  p {
    font-size: 1.15rem;
  }

  button {
    height: 3rem;
    width: 6rem;
    font-size: 1.25rem;
    color: white;
    background-color: #777;
    border-radius: 8px;
    border: none;
    transition: all 0.5s ease;

    &:hover {
      transform: scale(1.2);
      cursor: pointer;
    }
  }
}
</style>
