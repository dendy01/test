<template>
  <div class="main-container">
    <div class="container">
      <Header></Header>
      <Content :day="day" :month="month" :year="year"></Content>
      <Footer :day="day" :month="month" :year="year"></Footer>
    </div>
  </div>
</template>

<script setup>
  import Header from "./components/Header.vue";
  import Content from "./components/Content.vue";
  import Footer from "./components/Footer.vue";
  import { ref } from 'vue';

  const day = ref(new Date().getDate());
  let month = ref(new Date().getMonth());

  if (month.value < 10) {
    month.value = '0' + (month.value + 1);
  }

  const year = ref(new Date().getFullYear());
</script>

<style>
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

  .main-container {
    width: 100%;

    .container {
      width: 1000px;
      margin: 0 auto;
    }
  }
</style>
