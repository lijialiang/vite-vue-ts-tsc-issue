<template>
  <p v-if="fruit === Fruit.apple">
    apple
  </p>
  <p v-if="fruit === Fruit.banana">
    banana
  </p>
</template>

<script lang="ts" setup>
enum Fruit {
  apple = 0,
  banana = 1
}

const fruit = 0
</script>
