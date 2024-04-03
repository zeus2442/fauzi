<template>
  <div class="bg">
    <header>
      <img
        alt="fauzi logo"
        class="logo"
        src="./assets/fauzi1.jpg"
        width="250"
        height="250"
      />

      <div class="wrapper">
        <h1>FAUZI</h1>
      </div>
    </header>
    <Buttonc />
    <TextHeader />
    <HelloWorld />
  </div>
  <main>
    <TheWelcome />
  </main>
</template>

<script setup>
import HelloWorld from "./components/HelloWorld.vue";
import TheWelcome from "./components/TheWelcome.vue";
import Buttonc from "./components/Buttonc.vue";
</script>

<style scoped>
.wrapper {
  color: black;
  font-family: Impact, Haettenschweiler, "Arial Narrow Bold", sans-serif;
  text-align: center;
}

.bg {
  margin-left: 380px;
}
</style>
