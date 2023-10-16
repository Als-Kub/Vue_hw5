<template>
  <div>
    <hr />
    <h2>Часть 2. Задание Vue</h2>
    <h2 v-if="product.available">
      Car is available. Price - {{ formattedPrice }}
    </h2>
    <h2 v-else>Out of stock</h2>
  </div>
</template>

<script>
export default {
  data() {
    return {
      product: {
        name: "Car",
        price: 1000000,
        available: true,
      },
    };
  },
  computed: {
    formattedPrice() {
      return "$" + this.product.price;
    },
  },
};
</script>

<style scoped>
h2 {
  text-align: center;
  margin-bottom: 5vh;
}
</style>
