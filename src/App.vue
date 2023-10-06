<script setup>
import Header from "./components/Header.vue";
import Main from "./components/Main.vue";
import Card from "./components/Card.vue";
import Footer from "./components/Footer.vue";
</script>

<template>
  <div>
    <div class="body-top">
      <Header />
      <Main />
    </div>
    <div class="cards">
      <Card />
    </div>
    <div>
      <Footer />
    </div>
  </div>
</template>

<style scoped>

.body-top {
  background: #282828;
  min-height: 350px;
}
.cards {
  min-height: 420px;
  width: 50%;
  margin: auto;
  display: flex;
  position: relative;
  justify-content: center;
}
</style>
