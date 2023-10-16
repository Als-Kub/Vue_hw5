import ProductDetails from './components/ProductDetails.vue';
<template>
  <MainPage />
  <BlogPage />
  <BlogDetailsPage />
  <ProductDetails />
</template>

<script>
import MainPage from "./components/MainPage.vue";
import BlogPage from "./components/BlogPage.vue";
import BlogDetailsPage from "./components/BlogDetailsPage.vue";
import ProductDetails from "./components/ProductDetails.vue";

export default {
  components: { MainPage, BlogPage, BlogDetailsPage, ProductDetails },
};
</script>

<style lang="scss"></style>
