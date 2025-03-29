<script setup lang="ts">
const fun = () => {
  console.log('i love')
}

fun()

for (let i = 0; i < 100; i++) {
  console.log(i)
}

let str = "test hahaha";
</script>

<template>
  <div class="box">
    <h1>Me App</h1>
  </div>
</template>

<style scoped lang="scss">
.box {
  width: 600px;
  height: 400px;

  h1 {
    color: white;
  }
}

.logo {
  height: 6em;
  padding: 1.5em;
  transition: filter 300ms;
  will-change: filter;
}

.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}

.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
