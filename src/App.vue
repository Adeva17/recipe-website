<template>
  <div>
    <WebHeader></WebHeader>
    <home-page></home-page>
    <WebFooter></WebFooter>
  </div>
</template>

<script>
import WebFooter from "./components/footer/WebFooter.vue";
import WebHeader from "./components/header/WebHeader.vue";
import HomePage from "./components/pages/HomePage.vue";

export default {
  components: {
    HomePage,
    WebHeader,
    WebFooter,
  }
};
</script>
